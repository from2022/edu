# edu

the widget now can notify you when a status has changed
you will get a notification if:
your Homebridge stopped running
there is an update available for Homebridge
there is an update available for one of your plugins
there is an update available for node.js
disable notifications by setting notificationEnabled to false
enable getting notification when any status was yellow and is now back to normal by setting the variable disableStateBackToNormalNotifications to false
edit the variable notificationIntervalInDays to lengthen or shorten the time between getting the same notification (e.g. plugin update available) again
0 means you get a notification every time the script runs (not recommended)
1 means you get each possible notification to a maximum of 1 time per day
0.5 means you get each possible notification to a maximum of 2 times per day
Open a notification to reveal the "Show me!" button which takes you directly to Homebridge Config UI X
