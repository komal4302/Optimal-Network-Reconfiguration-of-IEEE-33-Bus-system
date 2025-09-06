🔌 Optimal Network Reconfiguration for Improved Microgrid Resilience
📖 Overview

This project focuses on optimal network reconfiguration of a distribution system to enhance microgrid resilience against faults and outages.
Using the IEEE 33-bus distribution system as a test platform, we implemented a reconfiguration strategy that minimizes load shedding, ensures efficient power delivery, and maintains radial topology under different fault scenarios.

🎯 Objectives

Develop and validate an optimal reconfiguration strategy.

Minimize total load shedding during contingencies.

Maintain radial network topology for operational simplicity and fault isolation.

Improve resilience and reliability of power distribution networks.

🛠️ Methodology

Test System: Modified IEEE 33-bus distribution system.

Approach:

Branch and Bound technique for optimal switching of tie switches (RCS).

Depth-First Search (DFS) to identify isolated buses.

Load shedding calculation for different fault scenarios.

Brute-force optimization to analyze reconfiguration possibilities.

Simulation Environment: MATLAB (with MATPOWER).

⚡ Key Features

Works for single, double, triple, and four-line fault cases.

Successfully minimizes load shedding under most fault conditions.

Ensures radial topology during reconfiguration.

Provides a fast solution with reduced time complexity.

📊 Results

3 simultaneous line outages → Network reconfigured successfully with zero load shedding.

4 simultaneous line outages → Complete reconfiguration not possible (system splits into subsystems).

Standard IEEE 33-bus system → Successful reconfiguration and power flow analysis without errors.
