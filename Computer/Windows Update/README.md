# Windows Update

---

## List
|n|Name|State|Path|Reg. path|Name|Type|Value|O/P|
|-|----|-----|----|---------|----|----|-----|---|
|1|Always automatically restart at the scheduled time|Disabled|`Administrative Templates\Windows Components\Windows Update\`|`Software\Policies\Microsoft\Windows\WindowsUpdate\AU`|AlwaysAutoRebootAtScheduledTime|REG_DWORD|Enabled value : 1<br/><br/>Disabled value : 0||
|2|Configure auto-restart required notification for updates|Enabled|`Administrative Templates\Windows Components\Windows Update\`|`Software\Policies\Microsoft\Windows\WindowsUpdate`|SetAutoRestartRequiredNotificationDismissal|REG_DWORD|Enabled value : 1<br/><br/>Disabled value : 0|
|3|Configure Automatic Updates|Disabled|`Administrative Templates\Windows Components\Windows Update\`|`Software\Policies\Microsoft\Windows\WindowsUpdate\AU`|NoAutoUpdate|REG_DWORD|Enabled value : 0<br/><br/>Disabled Value : 1||
|4|Remove access to use all Windows Update features|Enabled|`Administrative Templates\Windows Components\Windows Update\`|
|5|Do not connect to any Windows Update Internet locations|Enabled|`Administrative Templates\Windows Components\Windows Update\`|
|6|Specify Engaged restart transition and notification schedule for updates|Enabled|`Administrative Templates\Windows Components\Windows Update\`|
|7|No auto-restart with logged on users for scheduled automatic updates installations|Enabled|`Administrative Templates\Windows Components\Windows Update\`|
