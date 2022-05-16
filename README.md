# DataRemaining
A little [Tasker](https://tasker.joaoapps.com/) project that displays the data and number of days remaining for a US Mobile pool. The notification updates every 15 minnutes and will change to an alert when the data remaining falls below the threshold you specify.

# Setup
If you have [Tasker](https://tasker.joaoapps.com/) you can simply import this project. If you don't, there is a standalone APK you can install instead but be forewarned that it's a weird Tasker-generated app and probably isn't worth the trouble.

On first run it will prompt for a Pool ID and a threshold to start warning at (in GB). You can get the Pool ID by logging into your US Mobile account, selecting the pool you wish to monitor, and then grabbing the ID from the end of the URL.

If you ever need to change these values, run the `Initialize` task.