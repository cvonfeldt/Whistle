Usage:
Our app begins with a login/signup screen, where users can either sign in, create an account or skip for now.
On the feed screen, users can view posts and interact with them using like/dislike buttons (functionality not yet implemented), and can scroll to view more posts (currently we have three test videos).
The bottom navigation bar includes:

    Home Button – Returns to the feed screen.
    Like/Dislike Button – (Feature planned but not implemented).
    Upload Button – Navigates to the mock upload screen.
    Settings Button – (Feature planned but not implemented).

At the top right corner, there's a profile icon that navigates to a mock profile screen, displaying followers, following, and earned awards (awards have yet to be implemented). From the profile screen, users can navigate to the search screen, which contains:

    A search bar
    Mock trending hashtags for reference.

Users can return to the main feed via the back arrow and then the home button.
Additionally, we have an upload screen that serves as a mockup of the final design with planned functionality.

NOT FUNCTIONAL YET!!!!: The profile screen, search screen, upload page, and notifications are not functional yet. They are just mockups for now. We will fully implement these for the next release. 

Known Bugs:
-no known bugs 

Feedback wanted:

-What is good information to display on the home screen top bar? Your username? Your name? The name of the app? Other?
-Are there any unintuitive transitions?

Change log:
-added notifications screen
-implemented login/signup functionality using Firebase authentication
-implemented sample feed (fetch from internet)
-refactored code(converted hard-coded strings to string resources)
-implemented dark mode settings

Feedback received and addressed:

"The app crashed when I clicked on the notification button"
-This occurred because the notifications screen hadn’t been implemented yet. In this release, we completed that screen and connected the button to it properly, so the crash no longer occurs.

"Not much functionality yet"
-We've implemented a working login system, allowing users to sign up and log in. We've also added a basic version of the feed, which currently displays three test videos. For the final project, we plan to have full functionality in place, including the ability for users to create and view posts.

"Wasn't able to open it"
-This was due to the agp version, we reverted it to the class standard so peers should be able to run it.

"On upload screen, if you add a large amount of text into the text field... there's no way to scroll"
-We made the outlined text field scrollable. Users should now be able to scroll through large amount of text within the text field. 

"Dark mode on settings does not work"
-Dark mode was implemented in settings and works across the app. 
