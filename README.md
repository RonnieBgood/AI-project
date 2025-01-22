
# Predictive Ship Maintenance system

Final project for the Building AI course

## Summary

The Predictive Ship Maintenance System is an AI-powered solution designed to assist ship crews in enhancing vessel maintenance efficiency by predicting equipment failures. Vessel downtime due to mechanical failures disrupts operations and incurs significant costs. Current maintenance relies heavily on planned schedules based on hour and day counters in compliance with manufacturer recommendations. However, external factors like heat, humidity, and corrosion can lead to unplanned maintenance. By utilizing sensor data to account for these factors, the system can revolutionize maintenance procedures onboard, improving downtime management, reducing sudden mechanical failures, and saving costs.

## Background

Unplanned maintenance and breakdowns are common in maritime operations, especially for vessels operating in harsh environments like tropical or Arctic regions. The inability to predict these issues disrupts schedules and increases costs significantly.

- Unplanned Maintenance: Predicting mechanical failures caused by environmental factors helps reduce unexpected breakdowns.
- Inefficient Schedules: Current fixed maintenance schedules often lead to unnecessary or delayed servicing, wasting resources or causing failures.
- Costly Downtime: Unplanned mechanical issues often result in expensive delays and repairs.

Having spent over a decade in the maritime industry, I’ve experienced the challenges of unplanned maintenance and its impacts on crew operations and vessel performance. This project aims to improve operational efficiency and safety for maritime professionals.

The maritime industry is a backbone of global trade, yet it faces constant pressure to optimize costs and comply with stricter regulations. Introducing AI-driven predictive maintenance aligns with industry needs and promotes sustainable practices.

## How is it used?

Process of Using the Solution:
- Sensor Data Collection: Real-time data is collected from vessel sensors measuring engine performance, humidity, temperature, vibration, and other factors.
- AI Analysis: The system analyzes historical and live data to predict potential equipment failures or maintenance needs.
- Alerts and Recommendations: Maintenance teams receive timely alerts about predicted issues, including recommended timelines for servicing.

## Data sources and AI methods

Data Sources:
- Ship Sensors: Real-time data on equipment performance and environmental conditions.
- Historical Maintenance Logs: Data from past breakdowns and maintenance schedules.
- Third-Party Datasets: Weather and environmental condition datasets (e.g., humidity, salinity).

AI Methods:
- Predictive Analytics: Using machine learning models like LSTMs or Random Forests to predict failures.
- Anomaly Detection: Identifying abnormal patterns in equipment behavior using unsupervised learning.
- Visualization: Dashboards powered by AI for actionable insights.

## Challenges

- The system predicts failures but does not address how the maintenance should be carried out. It serves as a support system for planned maintenance. 
- The data can have biases depending on availability and quality of sensor data can vary between vessels.
- Adapting AI solutions to comply with strict maritime regulations.

## What next?

To ensure adoption, the system must comply with maritime regulations and undergo thorough validation. Future development includes integrating environmental monitoring for emissions compliance, scaling for smaller vessels, and partnering with industry stakeholders like shipbuilders and maintenance providers. Futhermore training and perhaps certification for end users is required to ensure understanding of the system.

## Acknowledgments

This idea stems from my career and life at sea. With over 10 years of experience in the maritime sector, I’ve gained insight into operational inefficiencies and areas for improvement.
