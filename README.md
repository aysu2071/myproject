# myproject

This is a simple AI project created for the Building AI course.

## Description
The program gives basic recommendations based on weather conditions using simple rule-based logic.

## How it works
- The user defines the weather
- The program outputs a recommendation

## Technologies
- Python
# Building AI course project
# Simple rule-based AI example

def recommend_activity(weather):
    if weather == "rainy":
        return "Stay at home and read a book"
    elif weather == "sunny":
        return "Go for a walk"
    elif weather == "cold":
        return "Drink hot tea"
    else:
        return "Have a nice day"

weather_today = "sunny"
print("Weather:", weather_today)
print("Recommendation:", recommend_activity(weather_today))
