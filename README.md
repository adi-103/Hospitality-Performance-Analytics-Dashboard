
---

# **HOSPITALITY PERFORMANCE ANALYTICS DASHBOARD**

### **Project Overview**
This hospitality project is a part of the resume project challenges hosted by Codebasics. The objective of this project is to provide critical insights to the revenue management team in the hospitality domain.

### **Domain**: Hospitality  
### **Function**: Revenue Analytics

---

### **About the Company**
**AtliQ Grands** is a leading hotel chain in India, owning multiple five-star hotels across the country. Despite their 20 years of experience in the hospitality industry, the company has recently faced challenges. Due to increased competition and ineffective decision-making, AtliQ Grands has seen a decline in market share and revenue in the luxury and business hotel categories.

As a strategic move to regain market share, the managing director of AtliQ Grands has decided to incorporate business intelligence and data-driven decision-making. However, they lack an in-house data analytics team and have engaged a third-party service provider to analyze their historical data.

---

### **Your Role**
You have been brought in as a data analyst to work on the following tasks:

1. Create relevant metrics based on the provided metric list.
2. Develop a comprehensive dashboard based on the mock-up provided by the stakeholders.
3. Derive additional insights beyond what is provided in the metric list or mock-up dashboard.

---

### **Key Metrics**
- **RevPAR (Revenue Per Available Room)**: Total Revenue / Total Rooms Available
- **OCC% (Occupancy Rate)**: Total Rooms Occupied / Total Rooms Available
- **ADR (Average Daily Rate)**: Total Room Revenue / Number of Rooms Sold
- **DSRN (Daily Sellable Room Nights)**: Available rooms for sale per day
- **Realization Rate**: URN (Utilized Room Nights) / BRN (Booked Room Nights)

---

### **Dashboard Requirements**
A list of visual metrics provided by stakeholders includes:

1. **Trends by Weeks**:
   - Revenue
   - Occupancy %
   - Average Rating
2. **Split by City**:
   - Revenue
   - Occupancy %
   - Average Rating
3. **Occupancy by Day Type (Weekday/Weekend)**
4. **Booking Percentage by Platform**
5. **Filters**:
   - Properties
   - City
   - Status
   - Platform
   - Month
   - Week
6. **Table** (to display the following metrics):
   - Hotel Property ID
   - City
   - Revenue
   - Occupancy %
   - Average Rating %
   - Cancellation Rate %
7. **Percentage Change** vs. Previous Month for each metric

---

### **Data Transformation and Modeling**
Using **Power Query** and **Data Modeling** techniques, the raw data was transformed into actionable insights. The relationships between different datasets were structured using a **Star Schema**, placing fact tables (such as revenue, occupancy, and bookings) in the middle and surrounding them with dimension tables (such as city, platform, and date).

Additionally, for context in the hotel industry, **Friday and Saturday** are considered weekends, and this distinction was taken into account while analyzing day-wise performance.

**Star Schema:** All the fact tables are in the middle and surrounded with the dimension tables.
 
 ![image](https://github.com/user-attachments/assets/75510ed5-4a53-4492-b8d4-080453fabadc)


---

### **Conclusion**
The hospitality performance dashboard highlights stable growth with opportunities for improvement. Targeting higher weekday occupancy, reducing cancellations, and driving more direct bookings are key areas to focus on. The insights provided here can help AtliQ Grands make informed decisions to regain market share and maximize revenue potential across properties.

--- 
