# Clima ![Author -Rehan Khan](https://img.shields.io/badge/Author-Rehan%20Khan-blue)

- A flutter weather application that can fetch live-weather information of any city in the world
- Try any city whose weather you wanna know!!

For help getting started with Flutter, view the online [documentation](https://flutter.dev).

You can check out the corresponding Google code lab [here](https://codelabs.developers.google.com/codelabs/flutter/index.html?index=..%2F..%2Findex#0).

# Demo

![Clima Gif](clima.gif)

---

<img width="217" alt="Screenshot 2020-04-17 at 10 01 31 AM" src="https://user-images.githubusercontent.com/42263217/79532535-0aebe100-8093-11ea-93fe-49b032be61dd.png">

The [Open Weather](https://openweathermap.org/current) was used to fetch data.

- Generate an api key here first by login into the website for one's own development purpose

- By geographic coordnates Api link was used:
  `api.openweathermap.org/data/2.5/weather?lat={lat}&lon={lon}&appid={your api key}`

- [Flutter Geolocator Plugin](https://pub.dev/packages/geolocator) was used to fetch the coordinates of location.

Click on run in Android studio/ type "flutter run" in terminal of VsCode and there you go!.


# Getting Started

**Note:** Make sure your Flutter environment is setup & if not installed then [Click here to install](https://flutter.dev/docs/get-started/install)

**Installation**

In the command terminal, run the following commands:

```
$ git clone https://github.com/khan-rehan/Clima-A-live-weather-App.git

$ cd Clima-A-live-weather-App/

$ flutter run
```

# Simulate for iOS

## Method One

```
Open the project in Xcode from ios/Runner.xcodeproj.
Hit the play button.
```

## Method Two

```
Run the following command in your terminal.
$ open -a Simulator
$ flutter run
```

# Simulate for Android

```
Make sure you have an Android emulator installed and running.
Run the following command in your terminal.
$ flutter run
```



