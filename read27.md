#  Android Tasks and Back Stack

first: 

` taska:`  a stack of activities that users interact with when performing a certain job. 
The activities are arranged in a stack, in the order in which each activity is opened. 



Note: 
if you opened a new activity and then backed on it this new activity would be popped of the stack and so on. 

 Activities in the stack are never rearranged, only pushed and popped from the stack


- the current activity starts another, the new activity is pushed on the top of the stack 

- The previous activity remains in the stack and the system retains the current state of its user interface, but is stopped 

- using the Back button,  the current activity is popped from the top of the stack AkA destroyed and the previous activity is resumed  AKA restored. 


- using the home button, the current activity is stopped and its task goes into the background. The system retains the state of every activity in the task. If the user later resumes the task by selecting the launcher icon that began the task, the task comes to the foreground and resumes the activity at the top of the stack.

____________________________________________ 


![](https://www.sitepoint.com/wp-content/uploads/2011/07/diagram_backstack1.png)



note that the activities in the back stack are never rearranged this allows to start a particular activity from more than one activity, a new instance of that activity is created and pushed onto the stack rather than bringing any previous instance of the activity to the top.

one activity in your app might be instantiated multiple times, you can modify it if you do not want an activity to be instantiated more than once.
## Managing Tasks:
* It uses for:
-  begin a new task when it is started (instead of being placed within the current task).
-  start an activity, you want to bring forward an existing instance of it (instead of creating a new instance on top of the back stack)
-  you want your back stack to be cleared of all activities except for the root activity when the user leaves the task.

1.taskAffinity
2.launchMode
3.allowTaskReparenting
4.clearTaskOnLaunch
5.alwaysRetainTaskState
6.finishOnTaskLaunch
##### And the principal intent flags you can use are:
1.FLAG_ACTIVITY_NEW_TASK
2.FLAG_ACTIVITY_CLEAR_TOP
3.FLAG_ACTIVITY_SINGLE_TOP

## Save key-value data

### SharedPreferences
- It uses to save small collection of key-values.
-  It is object points to a file containing key-value pairs and provides simple methods to read and write them.

* getSharedPreferences() — Use this if you need multiple shared preference files identified by name, which you specify with the first parameter.
* getPreferences() — Use this from an Activity if you need to use only one shared preference file for the activity.

