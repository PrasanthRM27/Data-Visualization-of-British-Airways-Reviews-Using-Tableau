### Steps to Build the Dashboard
Here’s the concise version of the process tailored for a GitHub README file:

---

# British Airways Review Dashboard

### Steps to Build the Dashboard

1. **Join Tables**  
   Merge BA Reviews and Countries tables using the Place column and the Country Column.  
   Validate the join for completeness and accuracy.  

2. **Average Metric By Country (Map)**  
   Use the Place column for geography and generate the map
   create the new parameter Pick a metric and the metrics which are in the data
   Create the calculated feild to use the metrics as filteres in the map 
   Give the coloring based on the avg of the selected metrics for the map.
   Add the required filters in the similar manner.

4. **Average Metric By Month (Line Chart)**  
   Plot Month-Year on the X-axis and selected metrics on the Y-axis.

5. **Average Metric By Aircraft (Dual Bar Chart)**  
   Create a bar chart showing `Average Rating` and `Review Count` side by side for each aircraft.

6. **Build the Dashboard**  
   Layout:
     **Left Sidebar**: Filters.  
     **Top Section**: Summary metrics.  
     **Main Section**: Map, Line Chart, and Bar Chart.  
   Link filters across all visualizations for interactivity.  

### Filters Used
- **Date**  
- **Seat Type** (Economy, Business, etc.)  
- **Traveler Type** (Business, Family Leisure, etc.)  
- **Aircraft Type**  

