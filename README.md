# Home Depot Search Relevance Analysis
## Natural Language Processing | Python | Text Analytics
### Project Overview
This project investigates how characteristics of customer search queries influence the relevance of product search results on Home Depot's e-commerce platform.

Using natural language processing (NLP), text preprocessing, and exploratory data analysis, my team and I examined the relationship between search intent, spelling accuracy, product measurements, numerical identifiers, and search relevance. 

The objective was to identify opportunities to streamline product discoverability and the customer search experience. 

### Tools and Technologies
- Python for data processing and analysis
- Pandas for data cleaning, merging, and feature engineering
- Natural Language Processing (NLP) for text analysis
- Text embeddings and cosine similarity for evaluating semantic relationships

### Methodology
1. ***Data Preprocessing:*** Cleaned and standardized product and search-query data, including measurement units, brand names, and product identifiers
2. ***Feature Engineering:*** Categorized search queries by characteristics such as brand names, product codes, spelling accuracy, and product dimensions.
3. ***Semantic Similarity:*** Explored text embeddings and cosine similarity to evaluate relationships between customer search terms and product information.
4. ***Exploratory Analysis:*** Compared relevance scores across search categories and examined how the placement of numerical information affected search performance.

### Key Findings
- ***Product titles matter:*** Searches containing numerical information were approximately 5x more likely to receive a perfect relevance score.
- ***Spelling affects relevance:*** Correctly spelled queries had a higher proportion of perfectly relevant results than misspelled queries.
- ***Search intent influences results:*** Brand-name searches achieved higher average relevance scores than searches involving model or product codes.
- ***Product dimensions matter:*** Search relevance varied depending on whether the product's displayed size matched the customer's requested dimensions.

### Business Recommendations
1. Implement intelligent spelling correction and search suggestions.
2. Encourage customers to specify measurement units when searching for products.
3. Improve product-title consistency by including relevant numerical identifiers and product specifications.

### Project Context
Completed as a collaborative academic project for the Master of Science in Analytics program at North Carolina State University.

The analysis demonstrates the application of NLP and data analytics to an e-commerce business problem.
