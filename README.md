# restaurant-data-analysis
# Restaurant Data Analysis Project

This project was completed as part of the **Cognifyz Data Analytics Internship**.  
The goal of the project is to perform exploratory data analysis (EDA) on a restaurant dataset to identify patterns in cuisines, ratings, pricing, geographic distribution, and restaurant chains.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset Description
The dataset contains information about restaurants including:
- Restaurant name
- Location (Latitude and Longitude)
- Cuisines offered
- Aggregate rating
- Number of votes
- Price range
- Online delivery availability

## Project Tasks

### Level 1 Analysis
- Identify the most common cuisines in the dataset
- Determine which cities have the highest number of restaurants
- Analyze the distribution of restaurant price ranges
- Examine the availability of online delivery services

### Level 2 Analysis
- Analyze restaurant rating distribution
- Identify common cuisine combinations
- Visualize geographic distribution of restaurants
- Detect restaurant chains and analyze their popularity

## Key Insights
- Most restaurants have ratings between 3 and 4, indicating generally positive customer experiences.
- Many restaurants offer multiple cuisine combinations to attract a wider range of customers.
- Restaurant locations tend to cluster in certain areas, showing high restaurant density in popular regions.
- Several restaurant chains appear multiple times in the dataset, indicating brand expansion across locations.

## Project Structure
plt.figure(figsize=(8,5))
plt.hist(df['Aggregate rating'], bins=10)
plt.title("Distribution of Aggregate Ratings")
plt.xlabel("Aggregate Rating")
plt.ylabel("Number of Restaurants")

plt.savefig("rating_distribution.png")
plt.figure(figsize=(8,5))
plt.hist(df['Aggregate rating'], bins=10)
plt.title("Distribution of Aggregate Ratings")
plt.xlabel("Aggregate Rating")
plt.ylabel("Number of Restaurants")


