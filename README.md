# MilaGroCantina
**This repo contains the generic overview and workflow done for milagro cantina.**


### Project Overview
This project involved developing a data-driven dashboard for Milagro Cantina to support strategic decisions aimed at boosting sales and profitability. The dashboard was designed to provide real-time insights into daily, weekly, and monthly performance metrics, helping the restaurant make informed adjustments to their menu, inventory, and staffing.

### Key Steps and Process

1. **Data Collection and Integration**:
   - Data was collected from multiple sources, primarily from the restaurant’s POS system and QuickBooks, to gather comprehensive information on sales transactions, inventory, and employee schedules.
   - A dedicated SQL Server was created to store and manage this data securely and efficiently, enabling seamless integration and retrieval across data sources.

2. **Data Refresh Automation**:
   - SQL Server Integration Services (SSIS) was configured to automate daily data refreshes. SSIS pulls the latest data from POS and QuickBooks, ensuring that the SQL Server database is continuously updated with fresh information. This automated process reduces manual intervention and ensures the dashboard reflects up-to-date metrics at all times.

3. **Data Storage and Processing**:
   - Using SQL queries, data was retrieved and processed to align with the dashboard’s requirements. Queries were structured to pull relevant information such as daily, weekly, and monthly sales, top-performing dishes, and employee-specific performance metrics.

4. **Dashboard Development**:
   - Built a dynamic dashboard with multiple pages, each tailored to provide specific insights:
     - **Sales Insights**: Visuals for daily, weekly, and monthly sales trends, highlighting top-selling dishes and highest-performing employees.
     - **Employee Scheduling**: A dedicated page for employee scheduling that aligns staffing with peak and off-peak hours, optimizing workforce management based on rush hour data.

5. **Data-Driven Recommendations**:
   - Based on dashboard insights, actionable recommendations were made to improve profitability:
     - **Menu Optimization**: Suggested combining popular dishes into meal packages offered at reasonable prices to enhance appeal and increase average ticket sizes.
     - **Inventory Optimization**: Proposed adjustments to inventory procurement based on sales patterns, reducing waste and optimizing stock levels for frequently sold items.

6. **Results**:
   - By implementing these recommendations, Milagro Cantina observed a noticeable increase in both sales and profit within the following month, validating the impact of data-driven adjustments.

### Technology Stack
- **SQL Server**: For data storage, management, and processing.
- **SSIS (SQL Server Integration Services)**: To automate daily data collection and integration from POS and QuickBooks.
- **Dashboarding Tool: POWER BI** Used to build interactive visuals for performance and employee scheduling insights.
