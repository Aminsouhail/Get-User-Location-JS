# Get User Location JavaScript Project

This project demonstrates how to retrieve the user's location using JavaScript and the geolocation API, and then fetch additional location details using the OpenCageData API.

## Demo

You can view a live demo of the project [here](https://aminsouhail.github.io/Get-User-Location-JS/).

## Overview

The main functionality of this project involves:

1. **Getting User's Location**: Upon button click, the JavaScript code retrieves the current latitude and longitude coordinates of the user's device using the geolocation API.

2. **Fetching Location Details**: Using the fetch API, a GET request is sent to the OpenCageData server, passing the obtained coordinates. This request returns all the location details corresponding to those coordinates.

## Why OpenCageData API?

The project utilizes the OpenCageData API to retrieve location details. It's important to note that storing API keys in client-side JavaScript files is not recommended due to security reasons. Instead, the server-side should handle API requests to keep the API key secure.

## How to Use

1. Clone the repository to your local machine.
2. Open the `index.html` file in your web browser.
3. Click the button to retrieve your location details.

## Technologies Used

- JavaScript
- HTML
- CSS

## License

This project is licensed under the [MIT License](LICENSE).

