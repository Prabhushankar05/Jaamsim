# ReadMe: Drive-Thru Optimization Simulation

## Project Overview
This project involved optimizing peak-hour operations for a local drive-thru store by leveraging simulation software and analytical tools (JaamSim and Python). The optimization efforts successfully reduced the average customer wait times from **6 minutes** to **1 minute and 30 seconds**. 

The primary objective was to evaluate and improve resource utilization of two kitchen stations (“drivethrough1kitchen” and “drivethrough2kitchen”) under various scenarios and replications.

---

## Key Components

### Tools and Technologies
- **JaamSim**: Used for building and running the simulation models.
- **Python**: Assisted in data analysis and visualization of simulation results.

### Key Metrics
1. **Utilization**: Percentage of time each kitchen station was actively utilized.
2. **Wait Time**: Average customer wait time (optimized from 6 minutes to 1 minute 30 seconds).

### Scenario Details
- **Scenario 1**: Simulated performance under typical peak-hour conditions.
- **Replications**: The scenario was replicated 30 times to ensure statistical reliability of results.

---

## Summary of Results
The table below summarizes the utilization metrics across 30 replications for the two kitchen stations:

| Kitchen Station          | Average Utilization (%) | Standard Deviation (%) |
|--------------------------|-------------------------|-------------------------|
| drivethrough1kitchen     | 49.71                  | 1.08                   |
| drivethrough2kitchen     | 97.47                  | 0.47                   |

### Observations
1. **drivethrough1kitchen**:
   - Utilization ranged between 44.19% and 56.57%.
   - Had a relatively balanced workload, with some capacity available for additional tasks.
2. **drivethrough2kitchen**:
   - Utilization consistently exceeded 95%.
   - Operated near full capacity, indicating it may be a bottleneck in the system.

---

## Conclusion
The optimization achieved a significant reduction in average customer wait times, from 6 minutes to 1 minute 30 seconds. However, the consistently high utilization of `drivethrough2kitchen` suggests that:

1. Further enhancements could focus on relieving this bottleneck (e.g., by redistributing tasks or introducing additional resources).
2. Monitoring and adjusting operations dynamically during peak hours could ensure continued efficiency.

---

## Files Included
1. **Simulation Model**: JaamSim files used for running the scenarios.
2. **Python Scripts**: Analysis scripts for processing and visualizing simulation results.
3. **Results Data**: CSV file containing utilization metrics for all replications.

---

## How to Run the Simulation
1. Open the provided JaamSim model files in JaamSim.
2. Run the scenario replication(s) by setting the desired number of replications.
3. Analyze the results using the provided Python scripts.

---

## Contact Information
For further questions or details, please contact:
- **Name**: [Prabhu Shankar]
- **Email**: [prabhushankargv@gmail.com]
