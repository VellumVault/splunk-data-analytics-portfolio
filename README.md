# Splunk Data Analytics: Ethereal Insights & Operational Intelligence
A deep dive into taking raw machine data and transforming it into actionable business intelligence using Splunk Enterprise.

## 🌊 Project Overview
In this project, I acted as a Security/Data Analyst for a fictional e-commerce site. The goal was to ingest raw web traffic logs, identify errors, and enrich that data with a product price list.

### Phase 1: Data Ingestion & Indexing
I started by uploading the raw `tutorialdata.zip` file.
![Dashboard View](1dashboard.png)

### Phase 2: Confirming Data Integrity
Once uploaded, I verified that Splunk was successfully indexing the events.
![Ingestion Success](2ingestion.png)

### Phase 3: Identifying Operational Issues
Using SPL (Splunk Processing Language), I filtered the logs to find 404 errors. 
![Search Query](3search.png)

### Phase 4: Visualizing Traffic Patterns
I created a visualization of client IP activity to see which users were interacting most with the server.
![Visualization](4visualization.png)

### Phase 5: Data Enrichment (The "Boom" Moment)
I uploaded a `Prices.csv` file and created a **Lookup Definition** to match messy `productId` codes with real product names and prices.
![Final Report](5final-report.png)

## ⚡️ Key Skills Demonstrated
* **Data Enrichment:** Using lookups to join disparate data sources.
* **SPL Proficiency:** Writing complex queries with `stats`, `table`, and `eval`.
* **Visual Analytics:** Creating dashboards to monitor client activity in real-time.
