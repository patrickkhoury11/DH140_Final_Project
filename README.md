# DH140_Final_Project

This content was created by Patrick Khoury.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/patrickkhoury11/DH140_Final_Project/main)

[Blog Link](https://patrickkhoury11.github.io/DH140_Final_Blog/posts/DH140_FinalProject.html)

Project Description:
In this project, I set out to examine song popularity in the streaming age of music with my principal research question: what key factors might differentiate songs as more “streamable” than others? In order to examine key factors, I further broke my research down into the following sub-question sets:
1. What is the relationship between key attributes and song genre? What is the relationship between key attributes and song era?
2. What is the relationship between key attributes and song popularity?
3. What is the relationship between song genre and song popularity? What is the relationship between song era and song popularity?
- Follow up: To what extent does a stream cap exist based on genre? Based on era? 

The data utilized in this project has been made accessible by the free and public web API provided by Spotify. Anyone can access this data by making an account with Spotify and authenticating yourself through the developer dashboard. After filling in the provided boxes in the “Create app” section, I am now able to utilize the user specific Client_ID and Client_Secret values it provides me with the access the free API. Utilizing the library "spotipy" on Python, I am able to retrieve relevant song data from any song, artist, or playlist of my choosing. For this project, I created a playlist myself featuring the top 1,525 streamed songs on Spotify using the information available on [this site](https://kworb.net/spotify/songs.html) that compiles the most streamed songs on Spotify. It is important to note that the aforementioned website updates daily, thus the stream numbers and placings have changed since I copied them for each respective song on July 24, 2023 at 11:35 AM.

![spotify](https://storage.googleapis.com/pr-newsroom-wp/1/2023/01/AppleCompetition-FTRHeader_V2-1440x733.png)
