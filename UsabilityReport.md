# Usability Test Report for Team G: Predestination

Over three days, our team conducted six usability tests with our stakeholders. We asked
our users to log in with Google Authentication and had them confirm that they succeeded by
finding their account page. Next, we provided users with a game code and asked them to join
that game session. None had issues entering the code. All users completed the given tasks in a
similar and straightforward manner up until this point.

Once our users joined the game session, they saw the statistics screen displaying a
dashboard, as well as a leaderboard with points and ranking of players in the current game. Our
test app contained mock data for all players on the leaderboard, except for the users’. When users
were asked what rank and how many points they currently had, three of the users relied on the
dashboard for the info, not the leaderboard. Four of the users noticed the inconsistency between
their rank on the dashboard and the rank on the leaderboard. We will work on integrating
leaderboard data with the data present on the dashboard to show consistency.

Next, users were tasked with selecting the lowest valued Clue so that they can start
playing the game. Most were able to navigate to the tracker tab where they found the “Select
Clue” button, which allowed them to select the Clue with the minimum amount of points. While
three Android users had more ease, three iOS users had trouble selecting the Clue because the
orb animation threw an error. Additionally, when presented with the Clue selection page, one
user pointed out that including “Points” after the numbers would clarify what the numbers mean.
We will work on these issues immediately.

Once a Clue was selected, the application returned to the tracker page with the animated
tracker orb. Here, we asked our users how close they are to the Clue’s location. Many found the
animated orb’s purpose intuitive and, combined with the “Keep looking” text indications, they
could tell that they were physically far from the destination. However, three users were slightly
unclear about other parts relating to this feature. One pointed out that the “Keep looking” text
indicator wasn’t very noticeable since it was located at the very top of the screen and not
particularly standing out. Another commented how these indications aren’t clear about closeness
to the location, perhaps due to the lack of a quantitative distance value. Another user pointed out
that the silly messages detract the user from understanding their location proximity to the clue.
As this is the most important screen for our app, we will work towards fixing the issues as soon
as possible.

Overall, users were satisfied with the app and logged out successfully after completing
the tasks. They all mentioned that this app would be fun for a future scavenger hunt and that they
would try it after we fix the communication issues.
