# Clustering-Analysis
This repository contains three projects that utilize different clustering techniques to analyze various datasets. Each project focuses on identifying distinct groups or clusters within the data and extracting insights for further analysis and decision-making.

# Approach

The project involves the following steps:
1. Data Preprocessing: Clean and prepare the survey data for analysis.
2. Exploratory Data Analysis: Explore the dataset to understand its structure and distributions.
3. Clustering Analysis: Apply clustering to identify distinct groups of engineering colleges.
4. Interpretation: Analyze the characteristics of each cluster and provide recommendations based on the findings.
   

# Engineering College Clustering (K-means)

### Context
Education is rapidly becoming a competitive sector with numerous institutions to choose from. To provide valuable insights to students, educators, and policymakers, RankForYou, a ranking agency, aims to analyze the state of engineering education in the country. As a data scientist at RankForYou, your task is to identify different types of engineering colleges based on survey data and provide evidence-based insights for an editorial article.

### Objective
Identify distinct segments or clusters of engineering colleges in the country and analyze their characteristics.

### Data Description
The dataset contains survey results from 26 engineering colleges, covering factors such as teaching quality, fees, placements, internships, and infrastructure. Each factor is rated on a scale of 1 to 5, representing very low to very high.

### Results and Recommendations
Three distinct clusters of engineering colleges were identified:
- **Cluster 0 (Tier 3 colleges)**: These colleges exhibit low teaching quality, poor infrastructure, and low placement opportunities. They should focus on improving teaching quality, infrastructure, and placement opportunities.
- **Cluster 1 (Tier 1 colleges)**: These colleges demonstrate high teaching quality, excellent infrastructure, and high placement rates. They can leverage their strengths to attract top candidates for placements.
- **Cluster 2 (Tier 2 colleges)**: These colleges have moderate teaching quality, infrastructure, and placement rates. They should invest in enhancing teaching and infrastructure to elevate their status.


# Product Segmentation Case Study (DBSCAN)

### Context
In the competitive world of athletic footwear, Adidas and Nike stand out as two major players, constantly vying for dominance in the market. As a newly appointed Data Scientist in a market research company, you've been tasked with extracting insights from the data of men's and women's shoes from these renowned brands. The goal is to perform an exploratory data analysis and cluster the products to identify similarities and differences between Adidas and Nike's product ranges.

### Objective
Analyze the product data from Adidas and Nike, identify key variables for clustering, and group products based on their characteristics.

### Data Description
The dataset comprises 3268 products from Nike and Adidas, including information such as listing price, sale price, discount percentage, brand, ratings, and reviews.

### Results and Recommendations
Two distinct groups of companies were identified:
- **Group 1**: These companies command premium prices due to perceived value and quality.
- **Group 0**: These companies struggle to consistently meet customer expectations despite offering competitive pricing.

### Recommendations:
- Group 0 should focus on improving product quality and promotional strategies to enhance customer satisfaction and brand loyalty.



# Tourism Investment Analysis (Hierarchical Clustering)

### Context
Tourism is a vital industry that significantly contributes to economic growth and development. As the tourism sector becomes increasingly measurable, data-driven analysis plays a crucial role in understanding key factors influencing tourism trends. As a Data Scientist in a leading tours and travels company, you've been tasked with analyzing various indicators of countries to identify prime locations for tourism investments.

### Objective
Explore key statistical indicators of countries and group them based on important factors to pinpoint strategic locations for tourism investments.

### Data Description
The dataset comprises essential statistical indicators of countries, covering general information, economic indicators, social indicators, environmental factors, and infrastructure indicators.

### Results and Recommendations
Three clusters of countries were identified:
- **Cluster 0**: These countries exhibit moderate internet usage, low to moderate healthcare and education expenditure, low GDP but a balanced economy.
- **Cluster 2**: These countries demonstrate high internet usage, moderate healthcare and education expenditure, moderate GDP with a slightly high dependence on services.
- **Cluster 5**: These countries show moderate internet usage, moderate healthcare expenditure, low education expenditure, and moderate GDP with a dependency on services.

Recommendations:
- Cluster 5 countries offer viable prospects for tourism services, but efforts to improve education and diversify the economy are necessary for sustainable growth.

## License

This project does not have a license and is provided for educational and informational purposes only. It is not open-source software, and you may not use, modify, or distribute it without explicit permission from the author.


