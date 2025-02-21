# SkyNav AI

## Overview
**SkyNav AI** is an advanced flight navigation tracker that visualizes and optimizes flight routes between multiple destinations. It processes complex flight data, including origin and destination cities, dates, flight durations, airlines, and layover times. The system helps users make informed decisions by analyzing direct and connecting flights, optimizing routes based on user preferences, and managing layovers efficiently.

## Features
### 1. Flight Data Representation
- **Graph-Based Visualization:** 
  - Cities as vertices, flights as edges.
  - Flight details (airline, duration, travel dates) stored in edges.
  - Implemented using a custom graph data structure.
- **SFML/GLUT Graphics Implementation:**
  - Nodes represent cities, edges represent flight routes.
  - Edge colors and widths denote flight durations.
  - Tooltips display flight details.

### 2. Flight Booking Feature
- **Flight Selection:**
  - Users select origin, destination, and date.
  - System suggests direct or connecting flights.
- **Layover Management:**
  - Ensures feasible layover durations.
  - Uses a queue for managing layover times.
- **SFML/GLUT Visualization:**
  - Highlights all possible routes.

### 3. Shortest and Cheapest Route Finder
- **Algorithm Implementation:**
  - Uses **Dijkstra’s Algorithm** and **A*** for optimal routes.
  - Implements priority queues using heaps.
- **Example:**
  - Finds the cheapest path from San Francisco to Tokyo with layovers.
- **Visualization:**
  - Highlights the optimal route in real-time with animations.
  - Final path is displayed with a glowing effect.

### 4. Custom Flight Paths and Preferences
- **User Preferences:**
  - Filters flights based on preferred airlines and transit cities.
  - Dynamically recalculates routes.
- **Visualization:**
  - Preferred cities marked with custom icons.
  - User-selected paths highlighted with distinct visual effects.

### 5. Layover Management with Queues
- **Queue-Based Approach:**
  - Ensures smooth flight transitions.
  - Manages layover times dynamically.
- **Visualization:**
  - Dashed lines for layovers.
  - Dynamic updates based on user selections.

### 6. Advanced Route Generation Using Linked Lists
- **Multi-Leg Journey Management:**
  - Each segment represented as a linked list node.
  - Dynamic adaptation to user changes.
- **Visualization:**
  - Arrows connect each stop.
  - Users can adjust routes interactively.

### 7. Graphical Query and Subgraph Generation
- **Subgraph Filtering:**
  - Displays routes relevant to user queries.
  - Filters out cities with no relevant flights.
- **Visualization:**
  - Excluded cities appear with reduced opacity.
  - Active routes remain bold and clear.

### 8. Advanced Algorithm Adaptations
- **Real-Time Pathfinding Visualization:**
  - Dijkstra’s and A* step-by-step evaluations.
  - Bidirectional search for efficiency.
  - Progressive highlighting of paths.

## Technologies Used
- **Programming Language:** C++
- **Graphics Library:** SFML or GLUT
- **Data Structures:**
  - Graphs
  - Priority Queues (Heaps)
  - Linked Lists
  - Queues
  
 ## Project Team
This project was completed by a group of three students, including myself.

  ---
**SkyNav AI** - A smarter way to navigate the skies! ✈️
