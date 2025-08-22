# Traffic NSGA-II Optimization Model

## Purpose
This NetLogo model simulates traffic flow at a T-junction and optimizes traffic light timings using a simplified **NSGA-II (Non-dominated Sorting Genetic Algorithm II)** approach and partial cellular automata featured vehicle agents.  
The goal is to reduce average vehicle waiting time and queue length at the intersection.  

---

## Model Implementation
- Written entirely in **NetLogo 6.x**.  
- Supports multiple lanes with turning and straight movements.
- Vehicle agents are given Celllular-Automata like behaviour.
- A turning logic is implemented as multiple lanes can be opened at once during color light implementation.
- Traffic lights operate in 4 phases and are dynamically optimized by NSGA-II after a fixed number of traffic light cycles (2).  
- Vehicles are spawned at lane start locations and follow simple movement and turning logic.  

---

## How to Run
1. Open the `.nlogo` file in **NetLogo 6.x**.  
2. Click **Setup** to initialize the environment.  
3. Click **Go** to start the simulation.  
4. Observe vehicle movement, lane congestion, and traffic light changes.  
5. Use **monitors and plots** within the NetLogo interface to track metrics such as:  
   - Average vehicle waiting time  
   - Queue length per lane  
   - Red/Green light durations  

---

## Plots and Monitors
- The model includes built-in NetLogo plots to visualize:  
  - **Waiting time over ticks**  
  - **Vehicle count per lane over ticks**  
- Monitors can display real-time values of traffic light durations, total vehicles, and other metrics.  

---

## Dependencies
- NetLogo 6.x  

---

## Data and Code Availability
All model code and plots setup are available on GitHub:  
(https://github.com/Lihini-2001/g1.git)

---

