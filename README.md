# budget-tracker

GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

You’ll need to use IndexedDB to add offline functionality. Review Module 18: NoSQL, Lesson 4: Add Offline Persistence with IndexedDB as a refresher on how to add this to your application.

You’ll also need to add a service worker to your application. Review Module 19: Progressive Web Applications (PWA), Lesson 4: Using Service Workers as a refresher on how to add this to your application.

Once you’ve updated the existing budget tracker, it should provide the following functionality:

The ability to enter deposits offline.

The ability to enter expenses offline.

Offline entries should be added to the tracker when the application is brought back online.