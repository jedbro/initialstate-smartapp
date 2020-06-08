# Initial State Hubitat App

This repository is a host of the Initial State Event Sender - a dirivitive of the SmartThings SmartApp forked for Hubitat Evolution, intended to make easy the process of sending events that occur on an HE network to Initial State for visualization.

### DIY Version

0. Sign up for a free trial, or free .edu account at www.initialstate.com
1. Create a new Bucket for your Hubitat data, and generate an access key
2. Copy the code from [`unbuffered-event-sender.groovy`](https://raw.githubusercontent.com/jedbro/initialstate-smartapp/master/unbuffered-event-sender.groovy)
3. Log in to your local HE server.
4. Navigate to App Code
5. Select "New App"
6. Paste the code copied from the unbuffered-event-sender.groovy
7. Edit line ~180 and replace `YOUR_ACCESS_KEY` with an access key from your Initial State account. Optionally, you can edit the bucket information above this line should you wish.
8. Select "Save"
9. Navigate to "Apps" section
10. Then "Add User App"
11. Click on this app to install.
12. Go back to Apps
13. Find this app now installed and add the devices you want / need
...
14. Give your devices some time to send their latest status
15. Go to www.initialstate.com 


You should now be all set! Please note, however, that events will populate the bucket automatically as new events happen on your Hubitat network. Your history of events will build from when you setup the SmartApp forward, so, if you don't see any events in your Initial State bucket immediately, it's most likely because no events have occurred just yet!

## This is all a fork of the fabulous work by [`David Sulpy`](https://github.com/davidsulpy/initialstate-smartapp) with minimal changes for Hubitat.
