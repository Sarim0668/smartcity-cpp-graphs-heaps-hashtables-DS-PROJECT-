# smartcity-cpp-graphs-heaps-hashtables-DS-PROJECT-
“Smart City simulation in C++ using graphs, Dijkstra, heaps, hash tables, trees and CSV data (stops, buses, hospitals, pharmacies, population).
<img width="1024" height="1024" alt="example" src="https://github.com/user-attachments/assets/f8482098-23c9-4f9a-ac2c-1b01e20eb02f" />

SMART CITY MANAGEMENT SYSTEM – ISLAMABAD

Roll NO: 

Abdullah Junaid(24i-0569)
Muhammad Sarim(24i-0668)
Muhammad Nawaz(24p-0733)
Section: CS-A


========================================

Data Structures & Algorithms Semester Project – Fall 2025
A complete multi–module Smart City simulation using Graphs, Trees, Hash Tables, Linked Lists, Heaps, Stacks,
and Queues.

----------------------------------------
1. INTRODUCTION
----------------------------------------
The Smart City Management System is a fully–integrated console-based simulation designed to digitally model
Islamabad’s transport network, education system, medical facilities, commercial centres, population
demographics, and public facilities.
Using advanced data structures and algorithms, the system mimics how modern cities manage routing, service
discovery, real-time analytics, and sector-wise connectivity.

----------------------------------------
2. KEY FEATURES
----------------------------------------
• Unified transport graph
• Modular Sub-Graphs: Google Maps–style filtering
• Real-time Query Functions
• Medical System-doctors, patients, hash-table lookup
• Education System: School Search, Performance Ranking
• Population & Sector System (N-ary trees, house allocation)
• Commercial System (Malls, product search)
• Public Facilities: routing, filtering
Transport Simulation - Queues, Linked Lists, Pathfinding

<img width="611" height="638" alt="edu2" src="https://github.com/user-attachments/assets/81fd4cc0-f8f1-49f6-b91e-e9fa1c961eb5" />


----------------------------------------
3. SYSTEM ARCHITECTURE OVERVIEW
----------------------------------------
Core controller: SmartCityCore.h
protected by the SmartCityTypes.h and Queue.h.
Graph-based routing, hash tables, priority queues, trees, stacks & queues.

----------------------------------------
4. DATA STRUCTURES USED
----------------------------------------
• Graph Adjacency List - Dijkstra, BFS
• Linked Lists – Bus routes
• Trees – Islamabad sector tree, school tree, population tree
• Hash Tables – O(1) lookup for citizens, buses, medicines etc.
• Priority Queues – Hospital & school ranking
overview • Stacks – Route history
• Queues – Management of passengers

----------------------------------------
5. FILE STRUCTURE
----------------------------------------
Source.cpp – Main entry point
SmartCityCore.h - Core system controller
SmartCityTypes.h – All data models
Queue.h – Linked queue + circular queue
Graph.h, Stack.h, MinHeap.h, Hash tables, Utilities


----------------------------------------
6. HOW TO RUN
----------------------------------------
Requires C++17+, CSV files in root directory.
Compile with:
g++ Source.cpp -o SmartCity
./SmartCity

----------------------------------------
7. MAIN MENU FEATURES
_________________________
Transport, Education, Medical, Commercial, Public Facilities, Population analytics.
<img width="465" height="267" alt="menu1" src="https://github.com/user-attachments/assets/826d6269-c338-491c-94c8-08ad9bbb8012" />
<img width="661" height="568" alt="tran2" src="https://github.com/user-attachments/assets/7c45ff3c-f52d-475c-b242-0e6d96d230f0" />
<img width="387" height="425" alt="tranMenu" src="https://github.com/user-attachments/assets/29ddefd0-7280-41a1-906b-be7beba785f1" />


----------------------------------------
8. ALGORITHMS IMPLEMENTED
----------------------------------------
Custom distance computation, Dijkstra’s shortest path, BFS, bubble sort for nearest neighbor ranking,
Hash-based O(1) search

----------------------------------------
9. SAMPLE OUTPUTS
----------------------------------------
Nearest Facility: F-10 Water Park
Distance: 1.24 km
Schools offering “Mathematics”: Beaconhouse, Roots Millennium

----------------------------------------
10. CONCLUSION
----------------------------------------
This Smart City model demonstrates how real-world city management problems can be solved with classical data
structures. The architecture is fully modular and extensible.

add the link in it please means how that image is displayed

