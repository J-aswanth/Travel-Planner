# ✈️ Travel Planner 
Travel Planner is a React-based web app where users can:
- Add and connect cities (nodes + weighted edges).
- Run graph algorithms like **Shortest Path (Dijkstra)** and **Minimum Spanning Tree (Prim/Kruskal)**.
- Visualize the algorithm execution step by step.
- Get travel plan outputs such as best route and minimum connection cost.

This project combines **Web Development (ReactJS + CSS)** with **Graph Algorithms (DSA)**.

## Features
- **Interactive Graph Builder**  
  - Click to add cities (nodes).  
  - Connect cities with routes (edges) and assign weights (distance/cost/time).  

- **Algorithm Selector**  
  - Shortest Path → *Dijkstra / A\**  
  - Minimum Spanning Tree → *Prim / Kruskal*  
  - (Future) Traveling Salesman Problem (TSP)  

- **Visualization**  
  - Animated Dijkstra expansion.  
  - MST edges highlighted as they are added.  
  - TSP cycle highlight (future).  

- **Travel Plan Output**  
  - Best route with cost/time.  
  - Minimum cost to connect all cities. 

## Getting Started

1. Install dependencies  
   ```bash
   npm install
   ```

2. Start the development server  
   ```bash
   npm start
   ```

   The app will be running at: [http://localhost:3000](http://localhost:3000)

---

## Screenshots

### Landing Page
![Landing Page](./app_overview/1.png)

### GraphBuilder Page
![GraphBuilder Page](./app_overview/2.png)

### Planner Page 
![Planner Page](./app_overview/3.png)
## Demo Video
[Click here to watch demo](./app_overview/travel%20planner.mp4)

