# AndroidEventMaker
A simple event maker for Android Pie +
This application's requirements were to develop an app with a login screen, which stores username and password data. After a user logs in or creates an account, the requirements state that there must be a grid layout screen for the user to view their events, as well as include an add, edit, and delete event buttons. The events are required to be stored in a local database. The application is also required to be asked if they would like to recieve SMS notifications regarding events. If the user does not authorize the request, the app should function as normal without the notifications.
The screens and features that support a user-centered UI for this project include a fluid and simplistic layout so that the user doesn't have to navigate too many screens in order to use it. The screens are tri-fold: Login screen, View events screen, and Add/Edit event screen. The design is successful in being a simplistic UI with no clutter.
The process of coding the app were to first create all of the screens that will be displayed, and then code the functions and interactions between those screens. This was done using both the android studio app builder, and the code-view structure. The Drag-and-drop builder was used for the most simple placement of elements, and the code-view was used to fine-tune the placement, edit the text displayed, and code all of the functionality and interactions between the screens and database. The strategy of creating first structure and then functionality was used in this project because of the way that android apps are structured and run, and because I wanted to have a visual for what I wanted the UI experience to look like for the user before I coded the back-end. This saved me time in the long-run because if I wanted to change something slightly about the structure or presentation of the screens, it would also likely require back-end adjustment.
While no JUnit or the-like tests were created, I was sure to test the app before submission to ensure that no crashes took place, and so that the app was properly storing and retrieving events, usernames, and passwords. I did this by doing manual testing; a slower and less methodical approach to testing. This was done so that a simple prototype could be up and running before in-depth tests took place, which takes a decent amount of time. The testing approach that I used revealed that the flow of the app worked well for the user, and that the events were displayed properly. In-depth testing definitely still needs to be done to ensure things like duplicate usernames or usernames and passwords with blank spaces don't exist, etc.
The process of creating and retrieving events for display was probably the most challenging part of the assignment for me, but after plenty of googling and asking all the questions I wanted, I was able to successfully overcome the challenge. It wasn't so bad. Luckily I already had some experience with SQL. The Intents were what got me for a bit but that's where stackoverflow came in handy.
I think that the fact that the app was actually completed ahead of time and that it actually looks like an app you'd see on the market gives tribute to my knowledge of Java and experience with the language. Again this app wasn't super complicated or ahead of its time but I'm glad that it turned out as it did, given my very limited experience with Android.
