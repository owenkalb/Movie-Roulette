# Weekly-Movie-Roulette
Initial Setup:
we used vscode to work on our project, we used the following extensions:
Django
Django Template Support
Python
Pylance
SQLite
SQLite Viewer
WSL
These must be installed to work, but at our current point: 12/3/24, the full template is not complete, but we plan to finish soon. So there will be a single file called HTMLHomepage.html that will be open for download. This file has all the current functionality that can be run without the full repo

For the full repo install, complete the following steps:
1. download all extensions
2. clone repo
3. cd into Movie-Roulette/Project
4. run py manage.py runserver
5. follow the link in the terminal to open the webpage

Steps to just see the webpage without downloading the full repo
1. Download HTMLHomePage.html file
2. open file

# User Manual
# Home Page
After opening the webpage in however way you choose to do so, you are sent to the home page.
The home page prompts you to select a week. Since this should be your first time, you will have to add the users in the group and then choose who they are assigned to and what movie they are assigned to watch. This will be done for every week. Make sure to save your changes before moving to other tabs.

# MyMovies
The next available tab is the MyMovie section. This tab allows the user to enter movies with the genres that they've watched. They can add as many as they want to. The goal for this on the user's side is to create a list of movies that they have watched so that they can keep track of them. This hasn't been implemented yet, but we would like to take these inputs for movies and genres to help populate our random movie generator since entering every movie can be tedious.

# Preferenecs
The preference tab is a section where you the user, select the types of genres and movie ratings that you are interested in. Once you select what you like, make sure to save these preferences. This hasn't been implemented yet but there will soon be a functionality where you can view your group preferences and assign movies based on them or choose different movies outside of their normal scope.

# Random Movie
This tab allows users to select a random movie from any or a specific genre. Once you select your choice, click the random movie button and wait for the wheel to finish spinning. Once it's done spinning, it will display a random movie of the selected genre. This tab is mainly for indecisive users who don't know what movie to recommend/assign or if they want to watch a random movie and don't know what to choose.

# Profile
Lastly, we have the profile section where you can click on the blank image in the top right of the webpage. Here this is where users should edit their display name, username, and password, and put comments inside the notes tab. This page is still in development and has little functionality since we aren't connected to our database yet.
