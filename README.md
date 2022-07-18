# World_Weather_Analysis
## Project Overview
The PlanMyTrip app team is beta-testing a new feature on their app platform to help users plan their trips based on weather preferences using real-time weather data.  After initial beta-testing, it has been requested to create a way for users to identify potential travel destinations and hotels to plan a multi-city itinerary.  This should conveniently be displayed on easy-to-read maps and markers.

## Results

Three different deliverables were created in order to achieve the final result:

1. API request using api.openweathermap.org to retrieve real-time weather data from a broad source of up to 2,000 random locations in order to get a large cross-section of choices for the user.

### Example of DataFrame


2. A filtered list is generated based on temperature preferences as inputted by the user.  Using additional API requests, closest hotel choices are added for each preferred city.  An interactive Google map with markers is generated so the user can view possible locations.

3. Once an itinerary is selected, final maps are created to show the travel route and current weather conditions in destination cities.
