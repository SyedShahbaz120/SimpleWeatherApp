# SimpleWeatherApp
"The Simple Weather App fetches current weather data from WeatherAPI and displays it with location, temperature, and condition. Users can search locations, toggle Celsius/Fahrenheit, and get weather for their current location."



Features
Retrieve current weather by entering a location parameter or tapping the Location button for current location
Display weather information including location name, temperature, and weather condition
Toggle between Celsius and Fahrenheit temperature units
Utilize Core Location for location-based services
Use UIKit for building the user interface

## Dependencies

The Simple Weather App relies on the following dependencies:

- Alamofire: For handling networking tasks
- SwiftyJSON: For parsing JSON data
- SDWebImage: For asynchronously loading and caching images

These dependencies are managed using CocoaPods. Make sure to install CocoaPods and run `pod install` before running the project.

## Using SF Symbols

SF Symbols is Apple's icon set that provides over 2,400 configurable symbols. To use SF Symbols in your project, simply refer to the symbol names provided in the Apple SF Symbols app or website and use them with `UIImage(systemName: "symbolName")`.

Usage
Enter a location parameter in the search box and tap Search to retrieve weather information.
Tap the Location button to fetch weather information for your current location.
Toggle the temperature unit switch to switch between Celsius and Fahrenheit.

## About

Developed by Syed Shahbaz.
