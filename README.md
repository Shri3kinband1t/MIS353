#MIS353 Projects
* W.I.S.H

## W.I.S.H
### Weather Is Stupid Hard

### Project Overview
Following the observation that many weather sites are cluttered, and mostly with information the user doesn't care about, I wanted to make one which is simpler than most and tries to be as brief and concise as possible. This is in the very early phases, it currently gets your location and does nothing with it, but is still live for [testing](lolfuckyou.com/mis353/index.html).

### Page Descriptions
* Index    Is where the user will be able to enter their preferences, and have their location detected. It will give them a new URL and send them to the weather page.
* Weather   Is where the weather will actually be displayed, and is meant to be bookmarked. (meaning the link will work repeatedly)

### Future Steps
* Making it actually get weather data, and hiding the API key required to do so.
* Implementing prettier UI on mostly the weather page, but the index could use it too.

### Competitor Analysis

* [OpenWeatherMap](https://openweathermap.org/city/4815352)
As far as design goes, the fast scrolling logos at the bottom are infuriating, and the  large banner image at the top means you have to scroll to get to anything useful. The url format however is simple with just /city/8484894 numbers representing a specific city. 
* [MerrySky](https://merrysky.net)
I personally like the design of this one a lot better. It's minimal but has all the information you could need, references and sources printed at the bottom. The URL shows nothing but coords.
* [NOAA National Weather Service](https://www.weather.gov/mob/forecast)
Beautiful in it's own government built sort of way. Basic yet cluttered at the same time. Has detailed and undetailed weather information in the same timespan (7 days) as the above sources. Some weird square pictures of conditions that really don't need to be there, and a map showing the area code you typed in that's basically useless. Lots of links for more resources though.

### Github Research
* [Overlayed Weather](https://github.com/jvicu2001/Simple-Weather-Overlay) Making weather simple may mean a website that displays minimal information with some sort of nice background. Maybe somebody might want that, I guess. I like his readme's inclusion of images and a list of features.
* [Somebody else's school project](https://github.com/R0shish/weather-site) Great design all around, especially in terms of layout and text styling. I want to use pieces of the css.

