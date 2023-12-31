# About The Project
The Weather Forecast Front-End Application utilizes a real-time weather API 
to deliver detailed weather information in three-hour increments. Integrated 
with the [MatchCityNameApi](https://github.com/KrzysztofTybinka/MatchCityNameApi) it features a responsive auto-complete city search bar. 
The application dynamically showcases distinct weather images based on the current 
search, providing users with a visually intuitive representation of weather conditions. 

# Usage
<img src="content/presentation.gif">

# Code
To display search bar with suggestions, application fetches api response and turns it into a valid json.  
<br />
<img src="content/matchCity.png">

When user chooses the city, latitude and longitude are being send to weather forecast api, and weather is set to current.  
<br />
<img src="content/cityChosen.png">

# Contributing
If you wish to contribute to this project, please feel free to create a pull request with your changes.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

