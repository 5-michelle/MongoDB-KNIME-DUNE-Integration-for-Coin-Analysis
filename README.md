# MongoDB-KNIME-DUNE Integration for Coin Analysis

## Project Overview
This project demonstrates an end-to-end data pipeline that integrates **MongoDB**, **KNIME**, **DUNE**, and **Python** to perform coin analysis. The workflow includes data extraction, analysis, and visualization. 

### Workflow
1. **Connect MongoDB with KNIME**  
   - Pull data provided by the professor from MongoDB using KNIME.

2. **Query Analysis with DUNE**  
   - Formulate prompts on DUNE to analyze the selected coin.
   - Dashboard: https://dune.com/michellelee/team2-memeproject2-bonk-analysis

3. **Pull Results from DUNE using Python**  
   - Retrieve analytical results using the DUNE API.

4. **Push Analysis Back to MongoDB**  
   - Store the DUNE analysis results into MongoDB using Python.

5. **Pull Data to KNIME for Visualization**  
   - Fetch the data from MongoDB to KNIME for further analysis and visualization.

---

## Technologies Used
- **MongoDB**: For data storage and management.
- **KNIME**: For workflow automation, data analysis, and visualization.
- **DUNE**: For blockchain data analytics and querying.
- **Python**: To automate DUNE API interaction and MongoDB operations.
- **DUNE API**: To programmatically fetch analysis results from DUNE.

