# 🌦️ Weather Station Simulator (C# Console App)

A beginner-friendly C# project that simulates daily weather conditions based on random temperatures. Designed to apply core programming concepts like conditionals, arrays, loops, and basic data analysis.

## 📌 Project Objective

To simulate realistic weather data (temperature + condition) over a user-defined number of days and generate basic analytics:
- Highest & Lowest Temperature
- Average Temperature
- Most Frequent Weather Condition

## 🔧 Tech Stack

- Language: C#
- Framework: .NET Core / .NET 6 Console App
- Tools: Visual Studio / VS Code

## 🧠 Concepts Practiced

- Arrays and control structures (`for` loop, `if-else`)
- Random number generation with `System.Random`
- Condition mapping (temperature to weather)
- Custom method writing
- Aggregation operations (`Max`, `Min`, average)
- Frequency analysis (most common condition)

## ⚙️ Logic Summary

- **Temperature Range:** -10°C to 40°C
- **Weather Mapping:**
  - ≤ 0°C → ❄️ Snowy
  - 1–15°C → ☁️ Cloudy
  - 16–30°C → ☀️ Sunny or 🌧️ Rainy (random)
  - > 30°C → ☀️ Sunny
- **Analytics:**
  - Max, Min, Average temperature calculated
  - Most common condition determined using nested loop frequency count

## 💻 Sample Output
Day 1: Temperature = 12°C, Condition = Cloudy
Day 2: Temperature = -3°C, Condition = Snowy
Day 3: Temperature = 27°C, Condition = Sunny
Day 4: Temperature = 31°C, Condition = Sunny
Most common weather condition: Sunny
Average Temperature: 16.8°C


## ✅ Why I Built This

As a beginner in C#, I wanted a practical project that connects programming with real-world concepts. This project helped me:
- Strengthen logic-building and array handling
- Learn to break problems into smaller functions
- Understand how to derive useful insights from raw data

## 🚀 How to Run

1. Clone or download the repo.
2. Open in Visual Studio / VS Code.
3. Build and run the console application.
4. Enter number of days when prompted.

## 📷 Screenshot (Optional)
*(Insert console output image here if available)*

---

> 🎯 **Open to feedback!** Let me know if you see any improvements or ways I can optimize this logic further.


