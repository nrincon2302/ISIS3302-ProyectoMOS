# Base Case Project - CVRP

## Overview

This project represents a base case of the Capacitated Vehicle Routing Problem (CVRP), using data provided in three CSV files: `clients.csv`, `vehicles.csv`, and `depots.csv`. These datasets contain essential information about the delivery network, including client demands, available vehicles, and depot locations.

## Key Considerations

- **ADDITIONAL VARIABLES**: Variables such as fuel price, fuel efficiency, maintenance cost, and driver wages are not included in the data. Students are encouraged to research and incorporate them into their analysis.

## Data Description ### 1. `clients.csv`

This file contains information about the clients that require deliveries. Key columns include:

- **LocationID**: Unique identifier for each location.
- **ClientID**: Unique identifier for each client.
- **Latitude**: Latitude coordinate of the client's location.
- **Longitude**: Longitude coordinate of the client's location.
- **Demand**: The quantity of goods required by the client in kg.

### 2. `vehicles.csv`

This file provides details about the vehicles available for deliveries. Key columns include:

- **VehicleID**: Unique identifier for each vehicle.
- **Capacity**: Maximum load the vehicle can carry in kg.
- **Range**: Maximum distance the vehicle can travel on a single fuel tank or full charge, in km.

### 3. `depots.csv`

This file contains information about the depots where vehicles are stationed. Key columns include:

- **LocationID**: Unique identifier for each location.
- **DepotID**: Unique identifier for each depot.
- **Latitude**: Latitude coordinate of the depot.
- **Longitude**: Longitude coordinate of the depot.

## Importance as a Base Case

This dataset constitutes a **common base case** for Projects A, B, and C in the course, as it establishes the minimum structure needed to address routing and logistics problems. From this base, each group can extend the model with different constraints and conditions:

### Project A: CVRP with Multiple Depots and Limited Stock

- Adds the **stock constraint** at each depot.
- Can be extended to multiple depots and load balancing among them.

### Project B: Hybrid Routing with Drones and Ground Vehicles

- Incorporates **different vehicle types** (e.g., 4x4 and drones), each with their own costs, speeds, and ranges.
- Adds **time windows** for deliveries.
- Adds **re-stocking** constraints for drones.

### Project C: CVRP with Refueling Nodes and Variable Costs

- Utilizes the same initial data.
- Adds **refueling stations**, range limitations, and **variable costs** related to energy or fuel consumption.
- Adds **tolls** and **weight restrictions**.
