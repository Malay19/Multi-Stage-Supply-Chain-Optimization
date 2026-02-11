# Retail Network Profit Optimization Engine

## End-to-End Pricing & Supply Chain Optimization

## Overview
This project builds a three-stage optimization pipeline to maximize profitability across a retail supply network.

The model integrates:
1. Store-level pricing optimization
2. Warehouse-to-store allocation
3. Transportation routing under time and capacity constraints

Final daily profit achieved: $58,920

---

## Business Objective
Maximize total network profit while respecting:
- Store demand curves
- Warehouse capacity limits
- Transportation costs
- Vehicle time and load constraints

---

## Stage 1: Pricing Optimization
- Modeled store demand using linear demand curves
- Optimized prices using AMPL
- Included pricing variance constraints based on travel time

---

## Stage 2: Warehouse Allocation
- Binary warehouse-store routing decisions
- Supply constraints and demand satisfaction
- Fixed and variable cost modeling
- Solved using Gurobi

---

## Stage 3: Transportation Routing
- Vehicle capacity: 500 units
- Max route time: 480 minutes (including unloading)
- Route feasibility constraints enforced

---

## Tools Used
- AMPL
- Gurobi Solver
- Python (data processing)
- Optimization modeling

---

## Key Takeaways
- Margin improvements drive larger profit gains than routing efficiency alone.
- Capacity constraints significantly shape route structure.
- Multi-stage modeling simplifies complex optimization problems.

<!--  ---

## Repository Structure
- `/pricing_model`
- `/warehouse_model`
- `/routing_model`
- `/notebooks` -->
