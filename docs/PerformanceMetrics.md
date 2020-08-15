# Performance Metrics

WARNING: Enabling performance metrics can use a lot of disk space if you are not careful. Around 1MB every 2 minutes. Turn this off when not needed.

AuraConnect can log performance metrics for debugging purposes.

To enable it, edit your appsettings.json file in the install folder for AuraConnect using a text editor.

This file can usually be found at C:\Program Files (x86)\ASUS\AURACONNECT\appsettings.json

Change the PerformanceMetricsEnabled value to true

```json
{
    "PerformanceMetricsEnabled": true
}
```

Restart the AuraConnect service for this to take effect.

The metrics will be added to the AuraConnect log located at C:\ProgramData\AuraConnect\logs\AuraConnect.log

Please upload the log as needed.
