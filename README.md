EcoGrid-Project is a comprehensive tool designed to manage and analyze the condition of systems, focusing specifically on roads, pipes and cables. This project uses data stored in CSV files (EcoGrid.csv) and uses machine learning techniques, specifically gradient boosting machines (GBM), to predict and track demand. The system can also record and report the impact of damage on buildings, providing details of emergency maintenance
This is the menu that we present the user with
1. Check Infrastructure Conditions: Enter a Road ID to view its details.
2. Add Disaster Details: Enter a Road ID and disaster details to update the dataset.
3. Urgent Roads with Disaster Details: View roads marked as urgent due to recent disasters.
4. Exit: Exit the application.

Dataset
The EcoGrid.csv file should have the following columns:

Road ID
Road Age (years)
Last Maintenance (years)_x
Road Condition
Pipe Material
Pipe Condition
Electric Cable Material
Cable Quality
Cable Condition
Last Maintenance (years)_y
Disaster Type
Disaster Year 
