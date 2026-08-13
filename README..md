# Adaptive Real-Time Traffic Light Simulator Based on Live Vehicle Count

**Course:** Engineering Capstone Project – 1 (23IE4053R/23IE4053A)
**Academic Year:** 2026 – 2027
**Department:** CSE, Koneru Lakshmaiah Education Foundation (KLH)

## Team Members

| S. No. | University ID | Name       |
|--------|---------------|------------|
| 1      | 2420030028    | P. Likhitha |
| 2      | 2420030076    | Karthika    |
| 3      | 2420030671    | Manasa      |
| 4      | 2420030677    | Vardini     |

**Supervisor / Guide:** Swapna Reddy

## Abstract

The Adaptive Real-Time Traffic Light Simulator Based on Live Vehicle Count is a smart traffic management system developed to improve the efficiency of traffic signals at road intersections. In conventional traffic signal systems, the green-light duration is usually fixed and does not change according to actual traffic conditions, which can cause unnecessary waiting time, congestion, fuel consumption, and delays — particularly when one road has significantly more vehicles than another.

The proposed system addresses this by dynamically controlling traffic signal timings based on the real-time vehicle count on each road. Vehicle counts can be obtained using sensors, cameras, or a simulated vehicle detection module. The collected data is analyzed to determine traffic density per lane, and the system automatically assigns an appropriate green-light duration accordingly — roads with higher density get longer green-light periods, while lower-density roads get shorter ones.

The simulator provides a visual representation of the intersection, including vehicles, traffic signals, vehicle counts, and dynamically changing signal timings, allowing users to observe how adaptive traffic control responds to changing traffic conditions. Minimum and maximum green-light limits prevent any lane from being blocked excessively.

The project aims to demonstrate how real-time data and adaptive decision-making can reduce average vehicle waiting time, minimize congestion, improve traffic flow, and potentially reduce fuel consumption and emissions. It also serves as a foundation for understanding intelligent transportation systems, extendable in the future using IoT devices, computer vision, machine learning, and live traffic data.

## Repository Structure

```
├── src/         # Source code for the simulator
├── docs/        # Documentation, abstract, diagrams, design notes
├── data/        # Sample/simulated data or data source references
├── results/     # Output results, screenshots, logs, evaluation data
├── reports/     # Phase reports, review submissions
└── README.md
```

## Setup & Execution Instructions

> _Update this section once the implementation stack is finalized (e.g., Python/Pygame, JavaScript, etc.)_

1. Clone the repository:
   ```bash
   git clone https://github.com/karthika-reddy/KLH-CSE-2026-27-2420030076-AdaptiveTrafficLightSimulator.git
   cd KLH-CSE-2026-27-2420030076-AdaptiveTrafficLightSimulator
   ```
2. Install dependencies:
   ```bash
   # e.g. pip install -r requirements.txt
   ```
3. Run the simulator:
   ```bash
   # e.g. python src/main.py
   ```

## Current Phase Status

- [x] Abstract submitted
- [ ] Requirement analysis / design
- [ ] Core simulation module implementation
- [ ] Adaptive signal-timing logic
- [ ] Testing & evaluation
- [ ] Final report & demo

_(Update this checklist as the project progresses through review-1, review-2, and final phases.)_

## Notes

- No credentials, API keys, or licensed datasets are stored in this repository.
- Repository access is granted to the Supervisor and Course Coordinator per project submission norms.
