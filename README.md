# Weather-App

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Functionality](#functionality)
* [Technologies](#technologies)
* [Setup](#setup)

## General info

Sample weather android app to get any location on Earth you want by city name or state code, implemented with lastest technology on android
Jetpack Compose [The modern ui toolkit for building native ui on android].

## Screenshots

<img src="images/1- Home.jpg" width="250"> <img src="images/1-2 Home.jpg" width="250">
<img src="images/1 - 3 More.jpg" width="250">
<img src="images/2- Search.jpg" width="250">
<img src="images/3- Search Details.jpg" width="250">
<img src="images/5- Temp Unit.jpg" width="250">
<img src="images/6- Add City.jpg" width="250">
<img src="images/7- Home.jpg" width="250">
<img src="images/7 - 2 Home.jpg" width="250">
<img src="images/7- 3 Home.jpg" width="250">
<img src="images/8- Search.jpg" width="250">
<img src="images/9- Search Details.jpg" width="250">
<img src="images/11- Temp Unit.jpg" width="250">
<img src="images/12- Add City.jpg" width="250">

## Functionality
- Forecast for next 5 days every 3 hours.
- Search any location you want by city name or state code.
- Suggested cities to know the current weather at this moment.
- More details for current air quality and other pollutants.
- Support dark theme and light theme.
- Support arabic and english language.


## Technologies

#### Languages:
- Kotlin 

#### User interface structure:
- Jetpack Compose

#### Architecture patterns:
- MVVM

#### Libraries:
- Retrofit            2.9.0 (https://square.github.io/retrofit/)
- Gson                2.9.0 (https://github.com/google/gson)
- Coil                1.3.0 (https://coil-kt.github.io/coil/)
- DataStore           1.0.0 (https://developer.android.com/jetpack/androidx/releases/datastore)
- Coroutine           1.6.4 (https://developer.android.com/kotlin/coroutines)
- Hilt                2.42 (https://developer.android.com/training/dependency-injection/hilt-android)
- Navigation          2.5.2 (https://developer.android.com/jetpack/compose/navigation)
- ConstraintLayout    1.0.1 (https://developer.android.com/jetpack/androidx/releases/constraintlayout)
- SplashScreen        1.0.0 (https://developer.android.com/develop/ui/views/launch/splash-screen/migrate)  

## Setup

- To run this project, install it by download or clone.
- Then regiser an account on this website https://openweathermap.org/api to acquire a new api key.
- Enter this api key in Constants object under API_KEY field [path: data/local/Constants]


#### System requirements
- Android Studio Dolphin | 2021.3.1 Patch 1
- Minimum sdk v21
- Target sdk v32
- Compile sdk v32
