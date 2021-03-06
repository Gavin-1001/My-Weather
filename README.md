# My-Weather - JavaScript Essentials Portfolio 2
![Index screenshot](https://github.com/Gavin-1001/My-Weather/blob/main/assets/images/github_screenshots/website_screenshot.png)
## Table of contents
* [General Introduction](#general-introduction)
* [User Experience](#user-experience)
	* [Target Audience](#Target-Audience)
	* [User Stories](#User-Stories)
		* [New User](#New-user)
		* [Existing User](#Existing-user)
		* [Site Developer](#Site-developer)
	* [Strategy](#Strategy)
	* [Project Goals](#Project-Goals)
	* [Future Works](#Future-Works)
	* [Images](#Images)
	* [Colours](#Colours)
	* [Wireframe Diagrams](#Wireframe-Diagrams)
	* [Fonts](#font)
* [Technologies](#technologies)
	* [Other Technologies](#Other-Technologies)
* [Issues](#issues)
* [Testing](#testing)
* [Deployment](#deployment)
*	* [Local Deployment](#Local-Deployment)
*	* [Remote Deploment](#Remote-Deployment)
*	* [Cloning/Forking](#Cloning/Forking)
* [References](#references)

## General Introduction:
The My-Weather application is an interactive website that allows users to input the location of a city and it will return the current weather in that city along with some weather variables such as humidity, pressure and wind speed/direction. The aim of the application as I have mentioned below is to give the user seemless experience when visiting the website and keep the front-end simple. 

## User Experience
### Target Audience
* General user
* People of all ages

### User Stories:
* New user: <br />
	i. I am a new user and I would like to check the weather. <br />
	ii. I am a new user and I would like an application with a easy navigable user experience. <br />

* Existing user: <br />
	i. I am an existing user and I would like to easily check the weather. <br />
	ii. I am an existing user and I would like a UI that is easy navigable. <br />
	

* Site developer: <br />
	i. I want to make the website interactive and a user friendly UI. <br />
	ii. I want to make the application easy to for users to enjoy. <br />

### Strategy: 
The strategy is to create an interactive weather application that displays the weather data in an clear and concise way. To create an application that provides
a consistency in styling across the application. To create code that allows for ease when implementing future updates and features.

### Project Goals:
* To provide an interactive application.
* Allows for users to query weather forecast.
* To provide an application that has good UX design.

### Future Works:
Futures works will include:
* Implementing a live weather map to visually view weather based on location. 
* Implement a more detailed weather description based on day of week.
* Implement a "Find my Location" button using Geolocaton.
* Implement a card display to allow for the temperature and other variables to be converted to imperial units. 

### Images:
* There are both icons and images that are used throughtout the application. The icons are from [Font Awesome](https://fontawesome.com/). All images are from the [OpenWeather API](https://openweathermap.org/weather-conditions). 

### Colours:
The justification for my choice the colours below are inline with the overall design flow. I chose to use a circular radial-gradient css function as it would allow me to use multiple shades of blue and would create a smooth transition from one colour to the next.
* Background colour - #1c7fc2, #009cdc, #0d9ade, #011844. 


### Wireframe Diagrams:
Before beginning the project I created 3 wireframe diagrams using the wireframe software Balsamiq. Below are links to the wireframe diagrams that the were used in development. When I started the project I initially chose to go with the second design, but later into the project when I began designing the front-end I chose to go with first design as I wanted to create a user friendly design. Below, you can see my wireframes designs for both Desktop and Mobile devices. 
* [Desktop](https://github.com/Gavin-1001/My-Weather/blob/main/Project_2_Wireframes/wireframe2.bmpr)
* [Mobile](https://github.com/Gavin-1001/My-Weather/blob/main/Project_2_Wireframes/Project_2_Wireframe_Mobile.bmpr)


### Fonts:
The fonts that are used in the project are from the Google Fonts library. Initially, I chose to use Open Sans and Quicksand, but after viewing the font in development I changed my mind and decided to use Noto Sans and Red Hat Mono. I have added san-serif as a backup in case there is an error with Google Font and the fonts cannot be loaded in.  

* All heading tags - [Noto Sans](https://fonts.google.com/noto/specimen/Noto+Sans?query=Noto+Sans), sans-serif. 
* All other tags - [Red Hat Mono](https://fonts.google.com/specimen/Red+Hat+Mono?query=Red+Hat), sans-serif.
	
## Technologies:
* [HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/Getting_started)
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [Bootstrap 5](https://getbootstrap.com/)
* [jQuery](https://jquery.com/)
### Other Technologies:
* [OpenWeatherAPI](https://openweathermap.org/api)
* [Google Font](https://fonts.google.com/)
<!--	
## Setup
To run this project, install it locally using npm:

```
$ mkdir folder
$ cd folder
$ git clone https://github.com/Gavin-1001/Gavin-1001.github.io.git
```
-->

## Issues:
* There is one issue that I am currently unable to resolve. In the index.html file I have the current weather components along the left hand side of the screen. The three components I have humidity, pressure and wind speed/direction. I am currently unable to display a label beside the humidity value, I have the label in the html code but it is not displaying on the screen. I plan to have this issue resolved in the near future. 

## Testing:
* For the testing portion of this project, I used W3C HTML Validation Service to validate my HTML, and again I used W3C CSS Validation to validate my CSS. Below I have linked the screenshots of my error free [HTML](https://github.com/Gavin-1001/My-Weather/blob/main/assets/images/testing_screenshot/validator%20images/HTML_Validation.png) and [CSS](https://github.com/Gavin-1001/My-Weather/blob/main/assets/images/testing_screenshot/validator%20images/CSS_Validation.png). 

To test the JavaScript I used an online compiler JSHint that shows errors and warning in JS code. I copied and pasted my JavaScript code into the textbox and I recieved only warning regard async functions. After researching the warnings on Google, I realised they are nothing to be concerned about, I learned that JSHint uses ES6 to compile code on the online tool, but you can configure the npm version of JSHint to compile on ES8. The screenshot of error free JavaScript code can be seen [here](https://github.com/Gavin-1001/My-Weather/blob/main/assets/images/testing_screenshot/js_hint_screenshot.PNG). 

To test the entire application I used a Chrome extension [Lighthouse](https://developers.google.com/web/tools/lighthouse#devtools). Lighthouse is an open-source, automated tool for improving the quality of web pages. I have attached a [screenshot](https://github.com/Gavin-1001/My-Weather/blob/main/assets/images/testing_screenshot/index_chrome_lighthouse_test_screenshot.PNG) of the automation testing report that was performed on the website.  

## Deployment:
### Local Deployment:
* Assuming you are using Gitpod, download the gitpod extension for [Chrome](https://chrome.google.com/webstore/detail/gitpod-always-ready-to-co/dodmmooeoklaejobgleioelladacbeki) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/gitpod/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search).
* Return to my github repository.
* On the upper right corner of the repository there is a green "Gitpod" button, click it, this will take you to Gitpod.
* Create an account if you do not have one, otherwise login.
* Github may ask you to authorize Gitpod. Click "Authorize gitpod-io.
* Gitpod will now open the repository.

### Remote Deployment:
* Visit my Github Repository.
* On the repository ribbon navigate to the "settings" tab.
* On the left of the screen, navigate to the "Code and automation" section.
* In the "Code and automation" section, click on the "Pages" button.

### Cloning/Forking:
#### Cloning:
* Navigate to the main page of the repository. 
* Above the file display/structure of the repository on the top right, click the green "Code" dropdown.
* To clone using HTTPS, copy the link using the clipboard icon. See [image](https://github.com/Gavin-1001/My-Weather/blob/main/assets/images/github_screenshots/cloning-repo.png) for reference on where to find the link to clone.
* Open a terminal/command prompt window.
* Create a folder to the location where you want to store the cloned repository. 
* In the terminal type, and press enter.

#### Forking:
* You are more than welcome to contributing to the repository, I look forward to seeing your work!
* To contribute to the project, navigate to the main page of the repository.
* In the top right hand corner of the webpage click the "Fork" button.
* You can now freely contribute to the project.
```
$ mkdir folder
$ cd folder
$ git clone https://github.com/Gavin-1001/Gavin-1001.github.io.git
```
* Open the folder in your favourite IDE, and the code should be displayed. 

## References:
* OpenWeather API [documentation](https://openweathermap.org/api)
* Mozilla [Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

