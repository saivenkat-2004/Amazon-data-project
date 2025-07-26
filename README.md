**Amazon Product Analysis: Laptops vs. Mobiles**
This project scrapes and analyzes data for laptops and mobile phones from Amazon to uncover trends in pricing, ratings, reviews, and specifications. 
The goal is to provide clear insights into what drives customer ratings and how brands position themselves in the market.

**Project Goal**
The main objective of this analysis is to answer questions like:

What is the average price and rating for laptops and mobiles?

Which brands are most popular based on customer reviews?

Is there a connection between a product's price, its discount, and its rating?

How do specs like RAM and storage differ between laptops and mobiles?

**How It Works**
The project follows these steps:

**Web Scraping**: A Python script using Selenium and Beautiful Soup automatically browses Amazon and collects data for laptops and mobiles. It gathers information such as:

Product Title

Price

Customer Rating

Number of Reviews

Brand

Discount

**Data Cleaning**: The collected data is cleaned using Pandas and Regex. This involves:

Extracting RAM and storage information from product titles.

Removing unnecessary text and symbols.

Handling missing values by filling them with the median.

**Data Visualization**: The cleaned data is visualized using Matplotlib and Seaborn to create plots and heatmaps that reveal relationships between different features.

**Key Findings**
Here are some of the interesting insights from the analysis:

**Price & Discount**
Laptops are generally more expensive than mobile phones, with some high-end models costing over ₹70,000.

Most products have a discount of 20-30%.

Interestingly, cheaper products often get bigger discounts, while more expensive ones sometimes have smaller deals.

**Ratings & Reviews**
Most top brands, like Lenovo, HP, Apple, and Samsung, maintain an average customer rating above 4.0.

Mobile phones tend to get far more reviews than laptops, with brands like iQOO and Samsung leading the pack.

**Specifications (RAM & Storage)**
The most common RAM for laptops is 16GB, while mobiles typically have 4GB or 6GB.

512GB is the standard storage for laptops in this dataset, compared to 128GB for mobiles.

**Tools Used**
Python: The core programming language.

Selenium & Beautiful Soup: For web scraping.

Pandas: For data cleaning and manipulation.

Matplotlib & Seaborn: For creating visualizations.

Jupyter Notebook: For organizing the code and analysis.
