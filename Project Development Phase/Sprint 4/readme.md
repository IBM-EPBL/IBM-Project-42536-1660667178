# Sprint 4
## In this sprint our task is to create a mobile application for the monitoring and control and to set up alert by both SMS and in UI alerts.

### The web UI in recreated to mobile application
The Web UI from previous sprint in converted/ recreated to mobile application. This process is carried out using Android Studio tool.
All the process are programmed using Java, the webview tool is used to achieve the process. It helps the project to access the web page through internet. 
To display the web socket (Node-red Dashboard), the app required both DOM Storage and App Cache permissions.

### SMS and Alert!
This part contains both SMS alert using Twilio Trail account service and in UI alert in dashboard page, UI alert is made with the notification node in node-red configured as to alert with pop up notification with a button as "Go to Motor Controls" when ever there is issues in primary parameters and push notification  when there is a issues in the secondary parameters.

#### UI Alert
The UI alerts are based on the parameters as discussed above. The feature is that, when there is a pop up message due to issues, there is option shown to Go to Motor Controls as a button, when the button is pressed, the UI is shifted to Motor Controls page.

#### SMS
Using Twilio Trail Account, the sms node is added to the node red at the condition function.

#### Condition Node
This node is the set the condition according to the dataset. The node is then connected to the SMS node.

All the required files are uploaded

Mobile App: [Water Monitoring.apk](https://github.com/IBM-EPBL/IBM-Project-42536-1660667178/blob/main/Project%20Development%20Phase/Sprint%204/Water%20Monitoring.apk) <br />
SMS ScreenShot: [SMS alert screenshot](https://github.com/IBM-EPBL/IBM-Project-42536-1660667178/blob/main/Project%20Development%20Phase/Sprint%204/SMS%20alert%20screenshot.jpg) <br />
Application user interface: [Mobile Application UI](https://github.com/IBM-EPBL/IBM-Project-42536-1660667178/blob/main/Project%20Development%20Phase/Sprint%204/Mobile%20Application%20UI.jpg) <br />
Application alert: [UI Alert](https://github.com/IBM-EPBL/IBM-Project-42536-1660667178/blob/main/Project%20Development%20Phase/Sprint%204/UI%20Alert.png) <br />
