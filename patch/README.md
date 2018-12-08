## Linux:

    sudo cat sblack.patch >>  /usr/lib/slack/resources/app.asar.unpacked/src/static/ssb-interop.js

restart Slack

## Windows 10:

Find your app in folder C:\Program Files\WindowsApps\91750D7E.Slack_3.3.3.0_x64__8she8kybcnzg4 (something like this) and copy it to any other folder. For example C:\Slack

If you couldn't open WindowsApp folder - take ownership on it. 
[uwp - Permission to access WindowsApps folder - Stack Overflow](https://stackoverflow.com/questions/52254719/permission-to-access-windowsapps-folder)

Then do the same:

    type slack.patch >> C:\Slack\app\resources\app.asar.unpacked\src\static\ssb-interop.js

start Slack from new location.

