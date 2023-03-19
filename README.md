# Lab-4-Life-Cycle

The activity lifecycle consists of a set of states through which an activity migrates, from creation to destruction. Each state in the activity lifecycle has a 
corresponding callback method that you can override in your Activity class to add behavior when your activity transitions into that state. Additionally, the Android 
logging API and specifically the Log class enable you to write short messages that are displayed in the Logcat within Android Studio. When your app goes into the
background, app data can be saved to a bundle using the onSaveInstanceState() callback, and retrieved using the onRestoreInstanceState() or onCreate() methods. Configuration changes, such as a device rotation, can trigger the activity lifecycle's
shutdown callbacks, and Android restarts the activity from scratch using the state bundle available to onCreate(). As with process shutdown, it is important to
save your app's state to the bundle in onSaveInstanceState().



