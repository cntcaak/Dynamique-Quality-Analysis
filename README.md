Project: Statistical Quality Control & Defect Reduction (Retrospective Analysis)

Context: Internship at Dynamique Industries, Secunderabad
Original Role: Quality Stage Inspector (Manual Inspection)
Project Focus: Application of Data Science to Manufacturing Quality

1. Executive Summary

During my internship at Dynamique Industries, I was responsible for the manual stage-wise inspection of machined components. This project revisits that experience to demonstrate how the Data Science and Machine Learning skills I have since acquired can be applied to optimize traditional quality control processes.

The goal of this study is to simulate the transition from manual logging to a data-driven decision-making framework.

2. Problem Statement (The Real-World Challenge)

The production line for Precision Gear Shafts was experiencing a rejection rate of approximately 8-12%.

The Issue: Inspection logs were handwritten, making it difficult to spot trends in real-time.

The Bottleneck: Root cause analysis was reactive (after failure) rather than predictive.

3. Methodology

This project bridges the gap between my mechanical background and my new AI capabilities.

Phase 1: Internship Experience (Manual)

Data Collection: Recorded deviations using Vernier Calipers and Micrometers.

Standards: Followed ISO 2859-1 sampling procedures.

Action Taken: Manually segregated defective parts and reported daily counts.

Phase 2: Modernization Project (Python & Data Analysis)

Simulation: I created a Python script to model the defect distribution observed during the internship.

Technique: Applied Pareto Analysis (80/20 Rule) using the pandas and matplotlib libraries.

Goal: To programmatically identify the "Critical Few" defects that caused the majority of rejections.

4. Data Analysis & Insights (Reconstructed)

Using Python to analyze the typical defect distribution of that production line, the following insights were visualized:

A. Defect Classification

Based on my shop-floor observations, defects typically fell into these categories:

Dimensional Deviation: ~45% (Oversize/Undersize)

Surface Finish Issues: ~25% (Roughness)

Burrs/Sharp Edges: ~15%

Other (Cracks/Geometry): ~15%

B. The Pareto Principle (Python Analysis)

The generated Pareto Chart highlights that Dimensional Deviations and Surface Finish accounted for 70% of total rejections.

Insight: A data-driven maintenance schedule for the lathe tools could have prevented the majority of these specific defects.

Note: The chart image is not displayed due to a local graphics rendering environment issue, but the analysis is verifiable in the attached quality_analysis.py script and its terminal printouts.

5. Root Cause Analysis

Focusing on the top defect (Dimensional Deviation), I identified the following contributors:

Machine: Tool tip wear causing gradual diameter increase over the shift.

Method: Lack of real-time Digitized Process Control (SPC) charts.

6. Proposed ML Solution (Future Scope)

If I were to return to this role as a Machine Learning Engineer, I would implement a Predictive Maintenance System:

Objective: Predict tool failure before it ruins the dimension.

Input Data: Spindle Current (Amps) and Vibration Sensor Data.

Model Architecture:

Logistic Regression: To classify the tool state as "Healthy" or "Degraded" (Classification).

Linear Regression: To predict the remaining useful life (RUL) of the tool.

This portfolio project demonstrates my ability to identify mechanical engineering problems and solve them using modern software tools.
