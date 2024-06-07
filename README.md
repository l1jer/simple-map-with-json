# Google Maps API Integration

This repository contains code to implement a custom Google Maps integration. It displays a map with a styled interface and custom markers for specific locations. This is ideal for showcasing business locations, event venues, or any place of interest on your website.

## Features

- **Custom Styles**: Apply aesthetic modifications to the map's visual elements.
- **Interactive Markers**: Clickable markers that open an information window with details about the location.
- **Responsive Design**: The map is set to fit the width of any device while maintaining a fixed height.

## Setup

To use this project, follow these steps:

1. **API Key**: Replace `GOOGLE_MAP_API_KEY` in the script tag with your actual Google Maps API key.
    ```html
    <script async defer src="https://maps.googleapis.com/maps/api/js?key=YOUR_GOOGLE_MAP_API_KEY&callback=initMap"></script>
    ```

2. **HTML Structure**: Include the following HTML to create a map container in your project.
    ```html
    <div id="map" style="height: 700px; width: 100%"></div>
    ```

3. **JavaScript Initialization**: Ensure the JavaScript provided is included at the end of your body tag or in a separate JavaScript file. Adjust the coordinates and content as necessary.

## Example

Below is a simple example of how the map is integrated and displayed using the provided code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Custom Google Map</title>
</head>
<body>
    <div id="map" style="height: 700px; width: 100%"></div>
    <script async defer src="https://maps.googleapis.com/maps/api/js?key=YOUR_GOOGLE_MAP_API_KEY&callback=initMap"></script>
    <script src="path_to_your_custom_script.js"></script>
</body>
</html>
```

Replace YOUR_GOOGLE_MAP_API_KEY with your actual API key and path_to_your_custom_script.js with the path to the JavaScript file containing the initMap function and related logic.

##Customization
You can customize the map style, marker icons, and information window contents by modifying the mapOptions, locations, and contentString variables in the script.
