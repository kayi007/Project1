# Duh! Travel Planner (Group Project #1)

View Here: https://truslide12.github.io/Project1/

# Overview

Project Description/Purpose of the App:
- Search for local events (e.g. Food, Clubbing, Tourist Funs)
- Add into your To-Do List (you can remove if you no longer want to attend the event and maybe send invite to friends through email)
- Play music in the background (maybe if we complete first two)

APIs used for this App:
- Yelp API (Day2: failed, does not support client-side API request/ change plans)
- Eventbrite API (Events) & Google Places API (restaurants)
- Google Map API
- Spotify API (maybe) 

Server Side Database:
- Firebase or Local Storage

APP Walk-Through:
1) A map of the United States (with a search button on the side)
2) User is required to type in a region area in search input or select an area on the map 
3) Then the user will move on to the category drop down box to select the events they want to do 
4) Once the user selects a category, all the event for that category will be displayed on the side 
5) User can scroll to see which will interest them, once they’ve decided, they can click on the event and that event will automatically added to User’s To-do list
6) User will be able to remove the event from the To-do list if they no longer interested

# Description: 
The Duh! Travel Planner was designed to allow people traveling to create and itinerary for their trip in one go. It solves the issues of not knowing what to do or where to eat when you're traveling somewhere new and not have to interchange between multiple tabs while doing your trip research and it also saves your itinerary online so you can look back at any time.

# Motivation: 
We had this idea and decided to built this app because we all love traveling and wants to make the most out of our trip, but doing all those research alone can be tiring if you’re traveling in groups, since everyone wants to do different things and there are conflicts. We also added the ability for users to add events they wish to create on their own. This adds flexibility for them to add special events not in our search or to visit locations that do not have web support (i.e. buildings, fountains, special location and visiting family, etc). 

# Result: 
Using Google Maps, Google Places, Eventbrite API and Firebase, we are able to create an app provides detailed restaurant reviews and nearby events info, and also provides real-time sharing, so that user can share the link of the itinerary to a group and everyone can contribute, change or remove things on the itinerary. 
This allows the user to look for a variety of restaurants and events based on their input in the search bar and via their selected choice from the dropdown menu. The user has the ability to search events and restaurants separately and then add the desired events/restaurants to their User Plan from the search list. 

# Individual Responsibilities & Team Effort:
(Ramon) Google Places: The Search section for user input (it can be a city, state, zip code or restaurant name)
Google Places API Call and Display restaurant detailed reviews on search result
2) (Carlos) Google Maps: A visual map to show the relative positions of events searched and the events selected
Google Maps API Call and GitHub approval & merging  
3) (Kathleen) Eventbrite API: taking user input area/region to find nearby local events and implement user customized radius for events
Bootstrap: Responsible for writing the UI for our html page to be mobile responsive
Using moment.js to translate event date and time to human readable 
Use Firebase database to store user selected events and restaurant, as well as data removal implementation on both html and Firebase

# Improvement & Challenges: 
The hardest part is when we have to merge everyone’s parts into one file. Because when we are testing our app, we used different ID names and different functions. We were using Google Maps search engine in our initial page, but realize that the search engine doesn’t work for both events and restaurants. It was also kind of redundant with the search engine in the main page. So we had to “kill the baby” in our initial page, but still keep the aesthetic look of our page. Due to time constraint, we were not able to implement the markers for all nearby events and restaurants. That is something we would like to improve on the project in the future. 

This project was a great challenge and allowed all of us to study deep into these complicated APIs, learn to work together and to merge the different sections of code we worked on in GitHub.

