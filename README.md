# Anne Arundel County 311 Service Request Analysis  

This project involves the analysis of service requests submitted through Anne Arundel County's 311 platform (SeeClickFix). The goal was to identify trends, highlight high-demand areas, and provide actionable recommendations for improving service delivery.  

## Project Objective  

Analyze the 311 service request data to:  
- Identify trends and patterns.  
- Highlight high-demand areas.  
- Provide actionable recommendations for optimizing service delivery and resource allocation.  

## Dataset  

- **Total Records**: 109,131 service requests  
- **Time Span**: October 2016 – August 2023  
- **Data Size**: ~20.8 MB  
- **Key Features**:  
  - `IssueID`: Unique ID for each request  
  - `RequestTypeTitle`: Type of service requested (e.g., pothole repair, recycling container)  
  - `IssueStatus`: Status of the request (open, closed, acknowledged)  
  - `DaysUntilClosed`: Number of days to close the request  
  - `Latitude/Longitude`: Geographic coordinates for request locations  
  - `Department`: County department responsible for handling the request  

## Tools and Skills Used  

- **Programming Language**: Python (for data cleaning and preprocessing)  
- **Visualization Tools**: Tableau, ArcGIS (for heatmaps and geospatial analysis)  
- **Techniques**: Data Analysis, Data Cleaning, Geospatial Analysis  
- **Skills Demonstrated**:  
  - Data Pruning  
  - Handling Missing Values  
  - Data Correlation Analysis  
  - Visualizing Trends and Insights  

## Key Insights  

1. **Departmental Performance**:  
   - The Department of Public Works (DPW) handled 75% of requests and had the shortest average closure time (~10 days), but the lowest user ratings (2.4/5).  
   - Planning & Zoning (P&Z) and Office of Information Technology (OIT) exhibited the longest closure times (~175-202 days).  

2. **Geospatial Analysis**:  
   - High activity was observed in urban districts (e.g., Districts 1, 2, 3, 5), while rural areas like District 7 showed fewer requests.  
   - Pothole reports were concentrated near major highways and high-traffic zones.  

3. **Communication Channels**:  
   - Walk-in and "Other" reporting methods had the fastest closure times (2-3 days), whereas phone and email methods faced significant delays (~80 days).  

## Recommendations  

- Increase resources for high-demand departments like DPW.  
- Streamline processes in P&Z and OIT to reduce delays.  
- Improve service quality in DPW to enhance user satisfaction.  
- Prioritize maintenance for areas with high pothole reports and recycling demands.  
- Optimize closure times for requests via slower communication channels.  

## Repository Contents  

- **`data.csv`**: The cleaned dataset used for analysis.  
- **`Final_Presentation.pptx`**: The detailed presentation summarizing insights and recommendations.  
- **`README.md`**: This file, providing an overview of the project.  

