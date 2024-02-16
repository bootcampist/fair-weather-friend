# fair-weather-friend

## Description
The Weather Dashboard displays the weather forecast for cities around the world using the Open Weather API. The weather is rendered to the page via JavaScript and CSS. The Open Weather API contained data for every three hours and so this was first sorted into the relevant days. The maximum temperature and humidity were calculated by sorting the data in descending order and the minimum temperature by sorting in ascending order. The weather icons were filtered to prioritise the day icons in the five-day forecast but to display the night ones if the data for the day is not yet available.
![screenshot-03](https://github.com/bootcampist/weather-dashboard/assets/152117886/d0b15677-8661-4847-94ea-d96a3f16e646)

![screenshot](https://github.com/bootcampist/weather-dashboard/assets/152117886/c653859c-a7dc-4149-9500-78e0381de883)

## Installation

N/A

## Usage
The desired city can be entered through the form input. This input is then used to find the latitude and longitude of the city which in turn is used to make a fetch request to the Open Weather API and retrieve the weather data. The user’s previous searches are displayed on the page in a list of buttons and are retained after the page is refreshed. The search history can be deleted by clicking the clear button.
[https://bootcampist.github.io/fair-weather-friend/](https://bootcampist.github.io/fair-weather-friend/)

## Credits

N/A

## License

Please see the LICENSE in the repository.
