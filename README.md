# Tableau Interactive Dashboard Project

## 📘 Overview
This project demonstrates the creation of an **interactive business dashboard** using Tableau Public.  
It utilizes the **Sample - Superstore** dataset to visualize key performance metrics, including **Sales, Profit, and Profit Ratio**, across categories, segments, and geographic regions.

Through this project, I learned foundational Tableau concepts, including:
- Connecting and relating multiple data tables
- Creating maps, charts, and text tables
- Combining views into an interactive dashboard

##Process
1. First, the dataset is imported. 
- has 3 tables (Orders, People, and Returns)
- Order & returns tables are imported with a many-to-many relationship
<img width="1920" height="900" alt="Screenshot 2025-10-23 145849" src="https://github.com/user-attachments/assets/a4d8c809-968b-4b18-a686-e580be2208ed" />


2. A new worksheet was created for each of the visualizations.


3. Profit ratio is created.
<img width="1920" height="898" alt="Screenshot 2025-10-23 110328" src="https://github.com/user-attachments/assets/dbfa3718-f91f-4c47-a772-65fc3b372264" />


4. Created a map visualization showing Profit Ratio across states.
   - color palette was set
   - value changed to percentage
<img width="1920" height="884" alt="Screenshot 2025-10-23 111051" src="https://github.com/user-attachments/assets/702f4679-985d-41e9-9e6f-c169b081a041" />

  - filters added with region
<img width="1920" height="907" alt="Screenshot 2025-10-23 111354" src="https://github.com/user-attachments/assets/ac149acd-153b-4a47-986c-14b0e4f50d96" />


  - filter added with the values
<img width="1920" height="954" alt="Screenshot 2025-10-23 111550" src="https://github.com/user-attachments/assets/20daa90e-e65b-4a6d-834a-a1bd0ab314d5" />


5. Visualized Sales Trends by Category and Segment using area plots (continuous).
<img width="1920" height="910" alt="Screenshot 2025-10-23 143818" src="https://github.com/user-attachments/assets/3e0f8789-3214-4e9c-a9fb-6e35ee9fee4b" />
<img width="1920" height="909" alt="Screenshot 2025-10-23 143912" src="https://github.com/user-attachments/assets/f74308b9-4204-4bf8-8714-5fbe8e82b9f7" />

   - created a Level of Detail (LOD) expression to find if the orders are profitable or not
<img width="1920" height="889" alt="Screenshot 2025-10-23 153135" src="https://github.com/user-attachments/assets/eeac285c-99f8-405d-a0b9-d278995bf1a3" />
Sales by Category
<img width="1920" height="881" alt="Screenshot 2025-10-23 161213" src="https://github.com/user-attachments/assets/b295e63b-6605-473e-b171-53a3ca5d2aed" />
Sales by Segment (with filter)
<img width="1920" height="875" alt="Screenshot 2025-10-23 161901" src="https://github.com/user-attachments/assets/73174fa2-f51f-48d7-adaa-b26ce48b10ff" />




