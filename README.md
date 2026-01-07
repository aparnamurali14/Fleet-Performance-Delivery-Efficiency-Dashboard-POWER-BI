# Fleet-Performance-Delivery-Efficiency-Dashboard-POWER-BI

## 🚚 Project Overview
This project aims to provide a comprehensive **AI-powered analytics dashboard** for a logistics company to monitor and optimize fleet performance. The dashboard analyzes fleet efficiency, on-time delivery rates, fuel consumption, and cost per kilometer, helping logistics managers make data-driven decisions.

The project is built using **Power BI** with advanced **DAX calculations** and **AI-powered visuals**.

---

## 📊 Dataset
The analysis uses the provided dataset: `logistics_project_dataset.xlsx` which includes:

1. **Trip_Data**  
   - Trip ID  
   - Vehicle ID  
   - Driver ID  
   - Origin  
   - Destination  
   - Distance (km)  
   - Fuel Consumed (liters)  
   - Delivery Status (On-Time / Late)  
   - Delivery Date  

2. **Vehicle_Master**  
   - Vehicle ID  
   - Vehicle Type  
   - Capacity  
   - Maintenance Cost
   - 
---

## 🎯 Project Goals
1. **Data Cleaning & Modeling**  
   - Handle missing fuel consumption values using **mean imputation**.  
   - Create a relationship between `Trip_Data` and `Vehicle_Master` via **Vehicle_ID**.

2. **DAX Measures**
   - **Fuel Efficiency** = Distance / Fuel Consumed  
   - **On-Time Delivery %** = On-Time Trips / Total Trips  
   - **Cost per km** = (Fuel Cost + Maintenance Cost) / Distance  
     > Fuel cost assumed as 100 per liter.

3. **Visualizations**
   - **Bar Chart:** On-Time Delivery % by Destination  
   - **Line Chart:** Fuel efficiency trend by Delivery Date  
   - **Cards:** Average Delivery Time & Average Cost per km  
   - **Pie Chart:** Vehicle Type vs Average Maintenance Cost

4. **AI-Powered Insights**
   - **Q&A Visual:** Example prompt - “Average Cost per km by vehicle type?”  
   - **Key Influencers:** Analyze delivery status based on distance, vehicle type, driver ID  
   - **Decomposition Tree:** Cost per km explained by Vehicle Type, Maintenance Cost, and Distance

---

## 🔑 Key Findings
- Vehicles with higher maintenance costs and older models tend to have **lower fuel efficiency**.  
- On-time delivery rates vary significantly by **destination**, highlighting areas for route optimization.  
- AI-driven insights identify **critical factors affecting delivery delays**, such as driver performance and trip distance.  
- Cost per km can be reduced by **optimizing fuel consumption** and **maintenance scheduling**.  

---

## 📌 Future Enhancements
- Integrate **real-time GPS tracking** for live delivery updates.  
- Implement predictive analytics for **fleet maintenance forecasting**.  
- Extend dashboard with **driver performance and route optimization AI models**.  

---
