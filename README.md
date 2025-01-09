# Project Title: Advanced Multi-Agent System for Anomaly Detection and Reporting (Version 2)

## Overview
This is the second iteration of a multi-agent system designed to leverage Large Language Models (LLMs) for advanced anomaly detection, narrative generation, and reporting. The system builds on its predecessor by introducing enhanced functionality for short- and long-term anomaly analysis, regression-based insights, and comprehensive reporting with interactive visuals and summaries.

## Key Features
- **Multi-Agent Architecture**:
  - **Agent 1**: Performs statistical anomaly detection on daily budget utilization values.
  - **Agent 2**: Executes regression analysis to detect anomalies in budgets and net bookings.
  - **Agent 3**: Handles short-term and long-term anomaly detection based on percentage and non-percentage metrics.
  - **Agent 4 (Overall Narrative)**: Combines outputs from all agents to generate interactive and comprehensive reports with visualizations.
- **Enhanced Analysis**:
  - Time-series anomaly detection using statistical and regression methods.
  - Aggregated reporting datasets for short- and long-term performance analysis.
- **Interactive Visuals**: Time-series trends, anomaly distributions, and other performance metrics are visualized interactively.
- **Detailed Summaries**: Reports include short and comprehensive summaries with observations and identified data issues.

## Tools and Technologies
- **Google Cloud Platform**:
  - **BigQuery**: For storing and querying time-series and aggregated datasets.
  - **Looker Studio**: For creating dynamic dashboards and visuals.
- **Python**:
  - Libraries: Pandas, Matplotlib, Scikit-learn, Seaborn.
- **Jupyter Notebook**: For agent workflow development and orchestration.

## Workflow
1. **Input Datasets**:
   - **Time-Series Dataset**: Used for daily anomaly detection (e.g., budget utilization and net bookings).
   - **Aggregated Report Dataset**: Provides percentage and non-percentage metrics for short- and long-term analysis.

2. **Anomaly Detection**:
   - **Approach 1**: Statistical anomaly detection for daily budget utilization.
   - **Approach 2**: Regression analysis for budget and net bookings.

3. **Short- and Long-Term Analysis**:
   - Analyzes performance based on percentage and non-percentage metrics.

4. **Interactive Reporting**:
   - Combines insights into a structured report with visuals and summaries.
   - Outputs both short summaries for quick decision-making and comprehensive narratives for in-depth analysis.

## Results
The system provides:
- Advanced anomaly detection using statistical and regression approaches.
- Integrated short- and long-term performance analysis.
- Fully interactive reports with dynamic visuals and actionable insights.

### Sample Report Output:
- **Visuals**: Detailed plots of anomalies and trends.
- **Short Summary**: Key observations and high-priority issues.
- **Comprehensive Summary**: In-depth analysis of anomalies and data issues.

## Repository Structure
- **Multi Agent System_V2.ipynb**: Jupyter Notebook implementing the advanced multi-agent workflows.
- **MindMap.png**: Visual representation of the multi-agent system's architecture and workflow.
  <img width="1209" alt="MindMap" src="https://github.com/user-attachments/assets/7d91a864-e1b8-4fc5-a99b-1659fba990f4" />
- **Sample Output**: Example structured report.

## Future Enhancements
- Incorporate predictive modeling for proactive anomaly detection.
- Add real-time data ingestion and reporting capabilities.
- Expand the scope of agents for more specialized analysis tasks.
- Introduce advanced visualization techniques for interactive storytelling.
