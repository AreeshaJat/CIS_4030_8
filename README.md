# CIS_4030_8
Cinequest: This is a Repo for CIS*4030 Group 8

## Project Description
Our app is called CineQuest, a movie encyclopedia app that provides users with a grand catalog of films for all-in-one place access to all information about movies. The problem we aim to solve with CineQuest is the lack of knowledge audiences potentially possess regarding their desired movies, for instance, audiences who do not know what a film is about before watching it, cast list, genres, etc. Also, we aim to solve the problem concerning the difficulty in choosing which movie to watch and making streaming choices in a diverse market. We identified this problem through our observation of the growing demand for personalized content consumption and the challenges users face in finding movies tailored to their preferences.

## Features and Functionality
**Welcome Screen:** 
The welcome screen presents you with the opportunity to sign in or sign up. New users will be required to click the sign-up button, where they will be required to create an username and password. Following this, they will complete a survey asking questions about your favorite genres, directors, films, etc, all to personalize their homepage to fit your movie interests. 

**Login Screen:**
Already signed-up users can log in to their already created Cinequest account by pressing the sign-in button, where they will be navigated to the sign-in form, and must enter their email and password. If you forget your password, the app asks for an email and passcode and then asks you to enter a new password and after doing so you get redirected to the home page. 

**Home Screen:**
The homepage displays a carousel of films, organized by trending movies, top-rated movies, and upcoming movies. The carousel automatically transitions to the next film for smooth animations. The films are fetched and retrieved by utilizing an async API call from the Movie Database, which allows us to retrieve a list of films per associated category, storing the data in a created Movie class through the provider library state management. Each film is clickable, navigating you to its movie page.

**Drawer:**
Each page either has a drawer or a back button. The drawer displays the options for the homepage, saved movies, settings, and logout. Clicking the logout option will navigate you back to the welcome page. Clicking the settings option will navigate you to the settings page, which will soon allow you to customize settings regarding your account, display, and so on. Clicking the homepage option will navigate you to the home screen. Finally, clicking the saved movies option will take you to the saved movies page.

**Saved Movies Screen:**
Each movie on the homepage has a clickable heart icon. When you click on the heart icon a pop-up message appears, “Movie Saved” and if you click on the heart again then a pop-up appears, “Movie Removed”. To view the list of favorited/liked films, you can navigate to the saved movies screen through the drawer. The favorite movies are displayed in a tile/list format, and clicking a film will navigate you to its specific movie page.  

**Movie’s Page Screen:**
The movie page displays the film’s title, poster, release date, and synopsis. Additionally, the page displays where the film can be watched. The page consists of three intractable buttons, view reviews, watch, and interact.  

**View Reviews Screen:**
The Movie Reviews Screen aggregates audience opinions, displaying a film's score and written feedback. It's a hub for users to read and engage with varied reviews, accessed via the "View Reviews" button on a film's page.

**Watch Screen:**
Navigate to the Watch Screen for a centralized selection of streaming services where the chosen movie is available. Tap your preferred platform or purchase options on Amazon or YouTube. Selecting any option will guide you towards the platform for immediate viewing. This is convenient for quick access to entertainment without the hassle of searching through different streaming services.

**Interact Screen:**
After selecting 'Interact' on a movie's page, users are taken to the Interact Screen. Here they can test their movie knowledge through a fun quiz that contains multiple-choice questions about various aspects of cinema, like movie eras or directors. Users make selections and can see their results at the end, making for an engaging way to learn more about films.

## Technologies Used

- Flutter
- MongoDB
- TMDB API

## How to Use
1. Clone this repository to your local machine.
2. Open the project folder in your code editor.
3. View the cinequest folder to explore the functionality.

## Screen Recording


https://github.com/AreeshaJat/CIS_4030_8/assets/106934155/92e23921-831e-4668-bb59-2f9807f3854f






