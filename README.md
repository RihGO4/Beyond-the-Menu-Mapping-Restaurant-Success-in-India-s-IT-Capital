# Beyond the Menu Mapping Restaurant Success in India's IT Capital
An end-to-end exploratory data analysis (EDA) of the Bengaluru restaurant ecosystem, focusing on market saturation, pricing strategies, and customer satisfaction metrics.
## Project Overview
In a city known as the "Start-up Hub" and "Pub Capital" of India, the restaurant industry is hyper-competitive. This project analyzes the Zomato Bangalore dataset to identify what makes a restaurant successful and where market gaps exist.

## Project Purpose
The project begins with data loading and initial exploration, followed by a robust data cleaning and preprocessing phase to handle missing values, correct data types, and normalize key features. We then proceed to a detailed exploratory data analysis (EDA) to visualize distributions, relationships, and patterns within the dataset. This includes analyzing restaurant concentration, service availability (online ordering and table booking), customer engagement metrics (votes), cuisine popularity, pricing strategies, and overall customer satisfaction through ratings. The analysis aims to identify dominant market players, high-performing locations, popular restaurant types, and effective value propositions.

The primary purpose of this project is to:

* Understand Market Dynamics: Gain insights into the structure and competitive landscape of the Bengaluru restaurant market.
* Identify Key Success Factors: Determine the factors that contribute to a restaurant's popularity and high customer satisfaction.
* Inform Business Strategy: Provide actionable recommendations for restaurant owners, potential investors, or even Zomato itself, regarding optimal locations, service offerings, pricing        strategies, and cuisine focus.
* Enhance User Experience: Understand customer preferences to potentially improve platform features or recommendations for Zomato users.
* Showcase Data Analysis Skills: Demonstrate proficiency in data manipulation, visualization, and interpretation using Python and popular data science libraries.

Ultimately, this project serves as a Strategic Playbook for understanding the intersection of geography, pricing, and consumer behavior in India's most vibrant food-tech market.

## Key Business Questions Addressed:
1. Market Penetration & Dominance: Which restaurant chains and types are most prevalent in Bengaluru, and what does this indicate about market saturation and opportunities for new entrants?
2. Customer Engagement & Popularity: Which restaurants and locations garner the most customer votes, and how does online ordering influence overall engagement and satisfaction?
3. Geographic Insights: Where are the "foodie" hubs in Bengaluru, and how do location and restaurant type correlate with average ratings and customer votes?
4. Cuisine Preferences: What are the most popular cuisines, and how diversified is the dining landscape in Bengaluru?
5. Pricing Strategies & Value for Money: How does pricing vary across different restaurant types, and which formats offer the best value for money in terms of cost-to-rating ratio?
6. Service Offerings Impact: What is the adoption rate of online ordering and table booking, and how do these services affect customer perception and restaurant performance?
7. Strategic Recommendations: Based on these insights, what actionable strategies can be recommended to Zomato for partnerships, promotional activities, and improving user experience, and for restaurant owners looking to optimize their operations
---

## Data Context
The dataset utilized contains records for over 12,000+ restaurants across Bengaluru. It includes critical variables such as location, cuisine types, average cost for two, aggregate ratings, and service availability. Through a rigorous cleaning pipeline, this raw data was transformed into a structured format suitable for advanced statistical visualization and strategic inference.

## The "Value Score" Metric
A core highlight of this project is the introduction of a custom business metric:
Value Score = (Rating)/(Average Cost)
This helps in identifying "Hidden Gems",i.e, restaurants that have high ratings but lower costs and visibility, providing an excellent opportunity for Zomato's promotional partnerships.

---

##  Tools Used
The following tools were used for data cleaning, processing, and visualization:
* Pandas & NumPy: Data manipulation and numerical analysis.
* Seaborn & Matplotlib: Advanced statistical plotting.
* Squarify: For hierarchical market share visualization (Tree Maps).
* WordCloud: For text-based popularity analysis.

To install dependencies, run:
pip install -r requirements.txt

---

## Repository Structure
```bash
├── README.md/               		# Raw dataset
├── main.ipynb/          			  # Jupyter notebooks with step-by-step analysis
├── requirements.txt/				    # Install dependencies
├── visuals_and_insights.docx/  # Exported charts and plots 
└── zomato.csv           			  # Project documentation

