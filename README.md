# DataRemaining
A little [Tasker](https://tasker.joaoapps.com/) project that displays the data and number of days remaining for a [US Mobile](https://www.usmobile.com/) pool. The notification updates every 15 minutes and will change to an alert when the data remaining falls below the threshold you specify.

# Setup
If you have [Tasker](https://tasker.joaoapps.com/) you can simply import this project. If you don't, there is a standalone APK you can install instead but be forewarned that it's a weird Tasker-generated app and probably isn't worth the trouble.

On first run it will prompt for the following:
1. A jwtToken
2. The Pool ID to monitor
3. A threshold to start warning at (in GB)

To get the jwtToken, log into the US Mobile dashboard with a desktop browser and use your favorite web developer tool to find the `USMAuthorization` header. Grab everything after the `Bearer `.

While you're in there, head over to the pool that you want to monitor. The POOL_ID is the token that comes after the `https://app.usmobile.com/dashboard/app/pools/` in the URL on the pool page.

If you ever need to change these values, run the `Initialize` task.
