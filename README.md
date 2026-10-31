# 🚁 Delivery Drone Flight Planner

**SDG 9 – Industry, Innovation and Infrastructure**

## 📌 Project Overview

The **Delivery Drone Flight Planner** is a web-based simulation project designed to find an efficient route for a delivery drone to visit multiple delivery locations and return to its starting point.

The project demonstrates how different algorithms can be used for pathfinding and route optimization while considering obstacles and estimated battery consumption.

It provides an interactive grid where users can place a drone base, delivery targets, and no-fly zones, then calculate and visualize the planned route.

## 🎯 Objectives

- Find an efficient route for a delivery drone.
- Visit multiple delivery locations and return to the base.
- Avoid obstacles and no-fly zones.
- Demonstrate pathfinding and optimization algorithms.
- Estimate distance, energy consumption, flight time, and remaining battery.

## ✨ Features

- **Interactive Grid:** Create and customize the drone's delivery environment.
- **Base Location:** Set the starting and ending point of the drone.
- **Delivery Targets:** Add multiple delivery locations.
- **No-Fly Zones:** Create obstacles that the drone must avoid.
- **Multiple Algorithms:** Choose between Held-Karp, Greedy, and Auto selection.
- **Route Visualization:** View the calculated route with drone animation.
- **Battery Estimation:** Calculate estimated energy consumption and remaining battery.
- **Scenario Presets:** Choose Urban, Rural, and Industrial environments.
- **Responsive Interface:** Use the application on desktop and mobile screens.

## 🧠 Algorithms Used

### 1. Breadth-First Search (BFS)

BFS is used to find the shortest path between two grid locations while avoiding blocked cells.

### 2. Held-Karp Algorithm (Dynamic Programming)

- Finds an exact optimal route for small delivery problems.
- Uses Dynamic Programming to solve a variation of the Travelling Salesperson Problem (TSP).
- Used for up to 11 total points, including the base.

### 3. Greedy Nearest Neighbor Algorithm

- Selects the nearest unvisited delivery location.
- Quickly calculates a route for larger problems.
- Provides a near-optimal solution but does not guarantee the shortest route.

### 4. Automatic Algorithm Selection

The Auto option selects:
- **Held-Karp:** For up to 11 total points.
- **Greedy:** For more than 11 total points.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Dynamic Programming
- Breadth-First Search
- Greedy Algorithm

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Open the project folder.
3. Locate the `index.html` file.
4. Open `index.html` in a web browser.
5. Select a base location.
6. Add delivery targets and no-fly zones.
7. Choose an optimization algorithm.
8. Enter payload and battery details.
9. Click **Compute & Animate Route**.
10. View the planned route and mission estimates.

No backend server or database is required.

## 📊 Performance and Simulation

The project displays the following estimated mission details:

- Total travel distance
- Estimated energy consumption
- Estimated flight time
- Remaining battery percentage

The battery reserve setting helps check whether the estimated mission meets the selected reserve requirement.

**Note:** Battery consumption and flight-time calculations use a simplified educational model. They are not validated real-world drone performance calculations.

## 🌍 SDG 9 Connection

This project supports **United Nations Sustainable Development Goal 9: Industry, Innovation and Infrastructure**.

It demonstrates how technology, algorithms, and intelligent route planning can contribute to more efficient delivery systems and innovative infrastructure solutions.

## 🔮 Future Enhancements

- Integration with real-world maps and GPS.
- Live weather information.
- More advanced route optimization algorithms.
- Realistic drone battery and payload models.
- Multiple-drone route planning.
- Real-time delivery tracking.
- Dynamic obstacle detection.

## ⚠️ Limitations

- This project is currently a browser-based simulation.
- It does not control an actual delivery drone.
- It does not use live GPS, weather, or airspace information.
- Energy and flight-time values are approximate educational estimates.
- Greedy routing does not guarantee an optimal solution.

## 👨‍💻 Project Status

**Status:** Completed Prototype

Developed as an academic project based on SDG 9 – Industry, Innovation and Infrastructure.

---

⭐ **If you find this project interesting, consider giving this repository a star!**
