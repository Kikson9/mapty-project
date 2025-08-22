# Mapty

Mapty is a workout mapping app built around **object-oriented JavaScript** and modern ES6+ features.  
It lets you log your running or cycling workouts on a map, using your current location as the starting point.

---

## Features

- **Geolocation API** → Automatically detects your location.
- **Leaflet Library** → Interactive map with workout markers.
- **Workout Types** → Running and Cycling, both extending a parent `Workout` class.
- **OOP Architecture** → Clean structure with separated classes and functions.
- **Private Fields & Properties** → Encapsulation for safer code.
- **Inheritance** → Specialized child classes for each workout type.
- **Local Storage** → Your workouts are saved and persist across reloads.

---

## Tech & Concepts

- JavaScript (ES6+)
- Object-Oriented Programming (classes, inheritance, private fields)
- Leaflet.js
- Browser APIs (Geolocation, Local Storage)

This project was a hands-on way to practice **good programming techniques**, logical structuring, and writing maintainable code.

---

## How to Use

1. Open the app in your browser.
2. Allow location access when prompted.
3. Click on the map to log a workout (choose Running or Cycling).
4. Enter details (distance, duration, etc.).
5. Workouts will be stored and displayed on the map and in a list.

---

## Project Structure

- `App` → Main controller class handling app logic.
- `Workout` → Parent class with shared workout properties.
- `Running` / `Cycling` → Child classes extending `Workout`.
- Use of private identifiers (`#property`) for better encapsulation.

---

## Why This Project

This wasn’t just about making a workout app — it was about writing **logical, well-structured code** with OOP in JavaScript.  
A lot of effort went into keeping the architecture clean, modular, and easy to follow.

---

## Demo

[Live Site](https://mapty-project-app.vercel.app)  
[Project Repo](https://github.com/Kikson9/mapty-project)

---

## Attribution

Originally based on [Jonas Schmedtmann's project] – modified and extended to fit my use case.
