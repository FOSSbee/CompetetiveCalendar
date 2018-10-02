# CompetetiveCalendar

This is an application supposed to help competetive coders keep track of challenges available on different platforms and plan accordingly. The plan is to roll out a google chrome extension and an android application version, both of which will be synced. We plan to give the user the option of adding events as in he/she likes and will also later add the functionality to choose websites to recieve pings from to be added to the calendar. Along with delete and remove options. The application will also have a reminder functionality to remind the user of the forthcoming challenge.

Another functionality could be to add tracks for the user to solve sample and older problems of similar challenges along with daily reminders so that the user can practice efficiently. And depending on his/her performance we can decide what next problem to provide him/her. *Need to come up with an algorithm for this*

Front end library and framework : BootStrap

Multi phase plan
```
a) Allowing the user to add items in their schedule so that the basic manifest file and front end of the app can be set up.

b) Then we plan to add functionality to allow users to select sites to get added in their schedule on its own to make it more convenient than before and should include making requests to the server of these sites. Another feature could be to register for the event from the extension itself.
```

Things to be added:

1. A toggle view system that allows the user to view schedule in extension box and in a new page
2. The add new item button should lead to the opening of a new page and the work should be synced there
3. We need to use some local storage mechanism to make sure that the user's data remains synced between different sessions, until phase 2 is completed where database will be integrated into the extension utility
