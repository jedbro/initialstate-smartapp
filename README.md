# Initial State Hubitat For  - WORK IN PROGRESS

This repository is a host of the Initial State Event Sender - a dirivitive of the SmartThings SmartApp forked for Hubitat Evolution, intended to make easy the process of sending events that occur on an HE network to Initial State for visualization.

### DIY Version

1. Copy the code from [`unbuffered-event-sender.groovy`](https://raw.githubusercontent.com/jedbro/initialstate-smartapp/master/unbuffered-event-sender.groovy)
2. Log in to your local HE server.
3. Navigate to App Code
4. Select "New App"
5. Paste the code copied from the unbuffered-event-sender.groovy
7. Select "Create"
8. Edit line 162 and replace `YOUR_ACCESS_KEY` with an access key from your Initial State account. Optionally, you can edit the bucket information above this line should you wish.
9. Select "Save"
10. Go to "Apps"
11. Then "Add User App"
12. Click on this app to install.
13. Go back to Apps
14. Find this app now installed and add the devices you want / need


You should now be all set! Please note, however, that events will populate the bucket automatically as new events happen on your SmartThings network. Your history of events will build from when you setup the SmartApp forward, so, if you don't see any events in your Initial State bucket immediately, it's most likely because no events have occurred just yet!
