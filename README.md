# data-analyst-Saini
Project Title: Understanding Animal Control Inventory

Objective:
The primary goal of this project is to conduct a descriptive analysis of the animal control register data for animals that have come into the custody of Vancouver Animal Control. Through this analysis, we aim to summarize key characteristics of the registered animals, including medical status, breed, color, and any known history. The insights generated from this analysis will inform strategies to improve the efficiency of animal control operations and enhance care for animals. The dataset spans 2023-2024 and provides critical details about the animals handled by the Vancouver Animal Control Office.

![animal-control-inventory-register](https://github.com/user-attachments/assets/62500012-7a5d-44c6-9eb9-25bb03542948)

Dataset:
The dataset includes the following key features, representing animals under Vancouver Animal Control custody during 2023 and 2024:

• AnimalID: A unique identifier for each animal.

• IntakeDate: Date the animal was taken into custody.

• MedicalStatus: Current health condition of the animal (e.g., healthy, sick, injured).

• Breed: The breed of the animal.

• Color: The color or fur description of the animal.

• History: Any known background information about the animal (e.g., stray, surrendered, lost).

• Location: The place where the animal was found or picked up.

• Description: Further details describing the animal and its condition.

• CustodyStatus: Current custody status of the animal (e.g., in shelter, returned to owner, adopted).

• OwnerName (if applicable): Name of the animal’s owner, if known.

<img width="959" alt="PORT" src="https://github.com/user-attachments/assets/5303fdba-cffa-4bd2-b16f-4ad98d82f690">

Data Collection:
The data was downloaded from the City of Vancouver's Animal Control Inventory site and stored in an S3 Landing Zone. The information provides a comprehensive view of the animals processed by Vancouver Animal Control over the years 2023 and 2024.

Data Cleaning and Structuring:
Using Amazon Glue DataBrew, the dataset was cleaned by removing missing values, unnecessary columns, and correcting data types where necessary. This step ensures consistency and reliability in the analysis.

Descriptive Statistics:
Key metrics to be calculated and analyzed include:

Animal Type (e.g., dog, cat, other)
Average Custody Time in 2023
Average Custody Time in 2024
Change in Custody Time over the two years
3. Data Visualization:
A Pareto chart will visualize the trends in custody time over time, showing how the number of animals in care changes across different months and years.

4. Animal Segmentation:

Segmentation by Medical Status: Grouping animals based on health conditions (e.g., healthy vs. injured) to analyze care patterns.
Segmentation by Intake Source: Segmenting based on the animal’s history or intake source (e.g., stray, surrendered, deceased).
5. Insights and Findings:
Insights derived from this analysis may highlight:

Peak intake periods (e.g., holidays, weekends)
Trends in the breed or type of animals taken into custody over time
Common health issues in animals processed by Vancouver Animal Control
6. Recommendations:

Based on the analysis, recommendations may include:

Adjusting staff levels or hours during peak intake periods to manage the workload efficiently.
Enhancing medical resources to better address common health conditions seen in animals.
Tools and Technologies:

Python (Pandas, Matplotlib, Seaborn) or Excel for data analysis
Data visualization tools (e.g., Excel) for creating clear, actionable dashboards
Deliverables:

A comprehensive report summarizing the methods, findings, and actionable recommendations.
Visualizations and dashboards to present key insights clearly to stakeholders.
A presentation to communicate major findings and suggestions for future improvements.
This descriptive analysis project will provide a deeper understanding of the animal control register in Vancouver, helping to optimize operations and improve the management and care of animals in custody.
