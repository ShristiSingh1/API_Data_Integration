# Power BI Integration Skills

This repository documents my journey of learning and implementing various Power BI data integration techniques. Below are the projects I have completed, along with detailed steps, demo videos, and insights into the skills acquired.

---

## 1. Power BI and REST API Integration
### **Overview**
This project involved integrating REST API data into Power BI and creating a dashboard to visualize key metrics.

### **Steps Taken**
1. **Understand the API**:
   - Used Postman to explore the API's endpoints and fetch sample data.
   - Familiarized myself with the JSON data structure.

2. **Connect API to Power BI**:
   - Used the **Web Connector** in Power BI to access the API endpoint.
   - Retrieved live data into Power BI using GET requests.

3. **Transform JSON Data**:
   - Used Power Query Editor to clean and shape the raw JSON data.
   - Converted nested data into tabular format for better visualization.

4. **Develop Dashboard**:
   - Built visualizations for KPIs such as trends, distributions, and comparisons.

### **Demo Video**
[Watch the API Integration Demo](https://drive.google.com/file/d/1I6wdTfykVnF2Yx05tTvNrqpn3V3eU2Q5/view?usp=sharing)

---

## 2. SQL Data Integration in Power BI
### **Overview**
This project focused on integrating data from a local SQL server into Power BI for visualization and analysis.

### **Steps Taken**
1. **Set Up Local Server**:
   - Installed MySQL Server and Workbench for database management.
   - Loaded sample data into the database using `.sql` files.

2. **Connect SQL to Power BI**:
   - Configured Power BI's **SQL Connector** to establish a connection to the local server.
   - Wrote SQL queries in Power BI to fetch specific tables and columns.

3. **Transform and Visualize Data**:
   - Applied data cleaning steps such as removing duplicates and handling null values.
   - Created interactive dashboards to display insights like sales performance and customer demographics.

### **Demo Video**
[Watch the SQL Data Integration Demo](https://drive.google.com/file/d/1niH275vI9519uXGTVQ6hbY_naAGCU81H/view?usp=sharing)

---

## 3. Excel to OneDrive Integration in Power BI
### **Overview**
This project involved automating data refreshes by integrating Power BI with Excel files stored on OneDrive.

### **Steps Taken**
1. **Prepare Data in Excel**:
   - Organized data into a clean and structured format in Excel.
   - Uploaded the file to OneDrive.

2. **Connect Power BI to OneDrive**:
   - Used the **OneDrive Connector** to link the Excel file with Power BI.
   - Enabled scheduled refreshes to ensure real-time updates.

3. **Create Dashboards**:
   - Built visualizations reflecting changes made in the Excel file.
   - Demonstrated automation by updating the Excel file and syncing it with Power BI.

### **Demo Video**
[Watch the OneDrive Integration Demo](https://drive.google.com/file/d/1P58eBJZ2vTN8uxCNRb9wVJavpeLMKtwl/view?usp=sharing)

---

## 4. Comprehensive Dashboard Development
### **Overview**
In this project, I combined data from REST APIs, SQL servers, and Excel-OneDrive to create a multi-page, department-wise dashboard.

### **Steps Taken**
1. **Data Integration**:
   - Merged data from multiple sources into a unified Power BI model.
   - Established relationships between tables for seamless analysis.

2. **Dashboard Layout**:
   - Designed an 8-10 page dashboard organized by department (e.g., Sales, HR, Finance).
   - Ensured each page catered to specific department needs.

3. **Advanced Features**:
   - Added slicers for interactive filtering.
   - Implemented DAX measures for custom calculations.

### **Key Features**
- Multi-source data integration.
- Professional-grade, interactive dashboards.

---

## Repository Structure
```plaintext
PowerBI_Integration_Skills/
├── API Integration
├── SQL Data Integration
├── Excel-OneDrive Integration
├── Comprehensive Dashboard
