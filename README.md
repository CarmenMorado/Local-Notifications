# Local-Notifications
100 Days of Swift (Project 21) Technique project about local notifications, which allow the sending of reminders to the user's lock screen to show them information 
when the app isn't running. Throughout the course of this project, I learned about UNUserNotificationCenter, requesting permission for notifications, the different
kinds of notification trigger, and more. In addition, I completed the following challenges:


-Update the code in didReceive so that it shows different instances of UIAlertController depending on which action identifier was passed in.


-For a harder challenge, add a second UNNotificationAction to the alarm category of project 21. Give it the title “Remind me later”, and make it call scheduleLocal()
so that the same alert is shown in 24 hours. (For the purpose of these challenges, a time interval notification with 86400 seconds is good enough – that’s roughly 
how many seconds there are in a day, excluding summer time changes and leap seconds.)


-And for an even harder challenge, update project 2 so that it reminds players to come back and play every day. This means scheduling a week of notifications ahead 
of time, each of which launch the app. When the app is finally launched, make sure you call removeAllPendingNotificationRequests() to clear any un-shown alerts, 
then make new alerts for future days.

![ezgif-3-9ed7b98d3c95](https://user-images.githubusercontent.com/42749527/114631230-35628100-9c8a-11eb-8b5a-1330a2eb2145.gif)
