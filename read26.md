# Android Fundementlals

- we can write Android apps using  kotlin,java or c++.
- the  Android application package(APk) which is an archive file with an .apk suffix contains all the contents of an Android app that allow the app to run and the file that Android-powered devices use to install the app in the phone device.

## App components: main building blocks of an Android app.
- **Activities**: represents the point where the user can  interact with the defrent parts of the application.
- **Services**:the main perpos for the services component to keep the app running in the background, for the services component its not provading ane contact with the users at self its just running the application in the background like music and maybe the user is using other app .
- **Broadcast receivers**:is a component that allow the system to deliver events to the app outside of a regular user flow, allowing the app to respond to system-wide broadcast announcements,  Because broadcast receivers are well-defined entry into the app and this help the system to deliver events to the apps currently  running.
- **Content providers**:set of  data that you can store in the file system, in a SQLite database, on the web, or on any other persistent storage location that your app can access.

## Intent
- An intent is created with an Intent object, which defines a message to activate either a specific component (explicit intent) or a specific type of component (implicit intent).
- For activities and services, an intent defines the action to perform.
- For broadcast receivers, the intent simply defines the announcement being broadcast.

## There are separate methods for activating each type of component:

- You can start an activity or give it something new to do by passing an Intent to startActivity() or startActivityForResult() (when you want the activity to return a result).
- With Android 5.0 (API level 21) and later, you can use the JobScheduler class to schedule actions. For earlier Android versions, you can start a service (or give new instructions to an ongoing service) by passing an Intent to startService(). You can bind to the service by passing an Intent to bindService().
- You can initiate a broadcast by passing an Intent to methods such as sendBroadcast(), sendOrderedBroadcast(), or sendStickyBroadcast().
- You can perform a query to a content provider by calling query() on a ContentResolver.

## The manifest file
- app must declare all its components in AndroidManifest.xml file, which must be at the root of the app project directory.

## Declaring components:
<?xml version="1.0" encoding="utf-8"?>
<manifest ... >
    <application android:icon="@drawable/app_icon.png" ... >
        <activity android:name="com.example.project.ExampleActivity"
                  android:label="@string/example_label" ... >
        </activity>
        ...
    </application>
</manifest>

- In the <application> element, the android:icon attribute points to resources for an icon that identifies the app.
- In the <activity> element, the android:name attribute specifies the fully qualified class name of the Activity subclass and the android:label attribute specifies a string to use as the user-visible label for the activity.

## Declaring app requirements
- it uses to prevent your app from being installed on devices that lack features needed by your app
- android {
  ...
  defaultConfig {
    ...
    minSdkVersion 26
    targetSdkVersion 29
  }
}