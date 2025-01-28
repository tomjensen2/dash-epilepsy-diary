# Interactive Seizure Diary Visualisation
A Python/Plotly.Dash Interactive epilepsy seizure diary

Epilepsy is a medical condition affecting approximately 65 million people worldwide.  Of these people ~30% fail to be effectively treated by anti-seizure drugs.  Many of these patients will be switching between different drug combinations with the aim of better controlling their seizures whilst recording when they have their seizures using a seizure diary.

In the absence of effective wearable medical devices Epileptologists ultimately have to judge the efficacy of a change in medication from the patients seizure diary, with limited time in office a good method for visualisation may be valuable to pick out trends in changes in seizures over time. 

This code is an adaptation of https://github.com/tomjensen2/Epilepsy_Seizure_Diary_visualisation and uses Plotly.Dash to generate an interactive seizure diary from diary data stored as .csv format.  It provides a clickable heatmap chart of seizure count vs hour that can be viewed with different binning periods.  And a comparison tool where two time periods can be easily compared 
![image](https://github.com/user-attachments/assets/cf6dcc2a-c8a8-47e2-aaa7-b048714020c0)

**To Do’s**
-- Adding Changes in Medication dosage to visualisations
-- Better/more relevant statistics
-- Sleep/exercise
