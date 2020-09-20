EggTimer - Final Code 
============================================================================

Solution code for Advanced Android with Kotlin Codelab 

Introduction
------------

EggTimer is a timer app for cooking eggs.
You can start and stop the timer, choose different cooking intervals.. 

In this codelab, working from this starter app, you:

* Add notitications to the eggtimer app.
* Use channels and importance for the app notifications. 
* Customize and style the notifications.


Pre-requisites
--------------

You should be familiar with:

* Services, AlarmManager, Broadcast Receivers.


Getting Started
---------------

1. Download
2. Swtich to start branch
3. Run the app.

Channel Importance Levels
---------------

* User-visible importance level

* Importance (Android 8.0 and higher)

* Priority (Android 7.1 and lower)


Makes a sound and appears as a heads-up notification (pops up at the top of the screen)

IMPORTANCE_HIGH

PRIORITY_HIGH / PRIORITY_MAX



Makes a sound

IMPORTANCE_DEFAULT

PRIORITY_DEFAULT



No sound

IMPORTANCE_LOW

PRIORITY_LOW



No sound and does not appear in the status bar

IMPORTANCE_MIN

PRIORITY_MIN



Note: To support devices running Android 7.1 (API level 25) or lower, you must also call setPriority() for each notification, using a priority constant from the NotificationCompat class.
