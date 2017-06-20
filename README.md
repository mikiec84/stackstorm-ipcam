# IP Cam Integration

Pack this allows integration with various consumer grade IP cameras.

## Configuration

**Note** : When modifying the configuration in `/opt/stackstorm/configs/` please
           remember to tell StackStorm to load these new values by running
           `st2ctl reload --register-configs`

## Actions

* ``capture_screenshot`` - Capture a screenshot and store it in a temporary file. Note: This action
  returns path to the temporary file where the screenshot is saved.
