---
language: javascript
tags: WIP, AJAX, data visualization, JavaScript library
resources: 2
---

# AJAX Visualization of Weather

## Objectives
* Learn how to use AJAX to keep data current.
* Use a JavaScript visualization library.

## Instructions
* Sign up for an account to generate a Weather Underground API key [here](http://www.wunderground.com/weather/api/d/login.html). You'll use this key for API calls.
* Require jQuery at the to of `index.html`. Double check that it was correctly required by typing `jQuery` in the browser console or just `$`. This should return a function, not "undefined".
* You'll be using Chart.js to visualize the JSON from Weather Underground so check it out [here](http://chartkick.com/). Require the Chart library in the head of your HTML file. Double check that you required the library correctly by typing `Chart` into the browser's console. A function should be returned, not "undefined".
* Require `weather-chart.js` below the lines where you required jQuery and Chart.js.
* In `weather-chart.js`, make a variable, `API_KEY`, and define it as the string of your Weather Underground key.
* Make a variable `URL` that will be the URL that your code will fetch hourly JSON data on New York city's weather. Read the [docs](http://www.wunderground.com/weather/api/d/docs?d=data/hourly) to figure out what it'll be.
* Use jQuery to [fetch the JSON](http://api.jquery.com/jquery.getjson/).


## Resources
* [Weather Underground](http://www.wunderground.com) - [Hourly](http://www.wunderground.com/weather/api/d/docs?d=data/hourly)
* [Chart.js documentation](http://www.chartjs.org/docs/#getting-started)