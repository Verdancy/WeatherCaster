![](https://img.shields.io/packagist/dt/Verdancy/WeatherCaster.svg) ![](https://img.shields.io/github/last-commit/Verdancy/WeatherCaster.svg) ![](https://img.shields.io/github/license/Verdancy/WeatherCaster.svg)

# WeatherCaster

This a is a WPF-MVVM weather forecasting tool that provides in-depth, three-day forecasts (including the current day) for any location, helping you plan and prepare for the days ahead.


## Requirements
- OpenWeatherMap [App ID](http://openweathermap.org/appid) (You will require an app ID that works with the 16 day API),
- Visual Studio 2015/17,

Once you get your App ID insert it as the value of the `APP_ID` constant in the `OpenWeatherMapService` class.
```csharp
private const string APP_ID = "PLACE-YOUR-APP-ID-HERE";
```

```vb.net
Private Const APP_ID As String = "PLACE-YOUR-APP-ID-HERE"
```

## Acknowledgements
- [OpenWeatherMap](http://openweathermap.org),
- [VClouds Weather Icons](https://vclouds.deviantart.com/art/VClouds-Weather-Icons-179152045),
- [MahApps.Metro](https://github.com/MahApps/MahApps.Metro)




