# WeatherAPP

Provides weather report of cities accross the world.


# Architecture: Clean Swift Architecture

VIP Clean Swift Architecture is used to develope Weather App. Clean swift architecture resolves massive view controller problem.

The view controller, interactor, and presenter are the three main components of Clean Swift. The view controller’s output connects to the interactor’s input. 
The interactor’s output connects to the presenter’s input. The presenter’s output connects to the view controller’s input.
Worker is responsible for providing data from API/Database to interactor. 
Router is responsible for navigating between view controllers.


# Cocoapods dependencies used

pod 'OHHTTPStubs/Swift' - Used to test app with fake network data (stubbed from file)

Note: run 'pod install' to project root directory.


# Completed User Stories:

As a User, I want to see a home screen with all the cities that are available on the API.

As a User, I want the cities be sorted alphabetically.

As a User, I want to be able to refresh the data that is on the home screen.

As a User, I want to be able to click on a city and see the weather results on a separate screen.

As a User, I want all the temperatures to be displayed in Celsius. The API returns also Fahrenheit and Kelvin, so they need to be converted:
Celsius = Kelvin - 273.15 Celsius = (Fahrenheit - 32) / 1.8

As a User, I want the temperatures to be displayed in chronological order.


Above User stories estimation = 7 hours.
Start Date = 2/12/2021
End Date = 7/12/2021
