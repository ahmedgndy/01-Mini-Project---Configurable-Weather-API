# 🌦️ Weather Config Demo

This project demonstrates how to use **configuration in .NET** with `appsettings.json`, environment-specific overrides, and dependency injection.

---

## 🔑 Features
- Read settings from `appsettings.json`
- Inject `IOptions<WeatherSettings>` into a Controller
- Switch environment-specific config (`Development`, `Production`)
- Expose an endpoint to read config values

---

## ⚙️ Example Configuration in Development Mode

```json
{
  "WeatherSettings": {
    "DefaultCity": "New York",
    "TemperatureUnit": "Fahrenheit"
  }
}
