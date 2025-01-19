# Zomato Data Analysis

## Project Overview
This project involves an in-depth analysis of restaurant data from Zomato to uncover key insights and trends. The analysis is performed using Python and various data visualization tools, focusing on categories, ratings, votes, and cost aspects of the dataset.

---

## Dataset
- **Source**: Zomato
- **File Used**: `Zomato data.csv`
- **Number of Records**: 148
- **Columns**:
  1. `name`: Name of the restaurant.
  2. `online_order`: Indicates if the restaurant accepts online orders.
  3. `book_table`: Indicates if the restaurant provides table booking options.
  4. `rate`: Rating of the restaurant.
  5. `votes`: Number of votes received by the restaurant.
  6. `approx_cost(for two people)`: Approximate cost for two people.
  7. `listed_in(type)`: Type/category of the restaurant.

---

## Key Tasks and Steps

### 1. Importing Libraries
Necessary Python libraries used in the project include:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

### 2. Data Cleaning and Preprocessing
- Conversion of the `rate` column from string format to a floating-point number by removing the denominator.
- Ensured there were no null values in the dataset.
- Summarized the data types and identified the structure of the dataset.

### 3. Visualizations and Analysis

#### a. Restaurant Types Distribution
- Created a count plot to represent the distribution of restaurant types using the `listed_in(type)` column.
- **Conclusion**: Majority of restaurants fall into the "Dining" category.
- ![image](https://github.com/user-attachments/assets/1b14d0ab-de62-4b07-a337-7facfe5c2ce2)


#### b. Votes by Restaurant Type
- Aggregated the total votes received by each type of restaurant.
- Plotted the results to show voting trends.
- **Conclusion**: Dining restaurants are preferred by more individuals.
- ![image](https://github.com/user-attachments/assets/2fd2d35b-94a7-4221-a263-8a333bebccdb)


#### c. Maximum Votes
- Identified the restaurant(s) receiving the maximum votes.
- **Result**: "Empire Restaurant" received the highest votes (4,884).

#### d. Top Restaurants by Online and Table Bookings
- Determined the top 3 restaurants for:
  - Online bookings.
  - Table bookings.
- Used sorting and grouping to derive results.

#### e. Restaurants Based on Cost (< 500)
- Categorized restaurants with an approximate cost for two people below 500.
- Determined the top 5 categories and their leading restaurants based on ratings and votes.
- **Results**:
  - Top categories: Dining, Cafes, Buffet.
  - Examples: "Corner House Ice Cream" (Rating: 4.3), "Frozen Bottle" (Rating: 4.2).

#### f. Rating Distribution
- Analyzed the distribution of ratings across all restaurants.
- Visualized the mean and median rating values.
- ![image](https://github.com/user-attachments/assets/37717755-bdbc-4ddb-8467-d7e7b59ec6f0)


---

## Results and Conclusions
1. **Preference**: Dining restaurants dominate in both popularity and customer preference.
2. **Top Performing Restaurant**: "Empire Restaurant" stands out as the most voted restaurant.
3. **Affordable Dining**: Most affordable restaurants (<500 cost) belong to the Dining category.
4. **Ratings Insight**: Ratings exhibit a balanced distribution, with mean and median values close to each other.

---

## How to Use This Project
1. Clone the repository and ensure the dataset (`Zomato data.csv`) is available.
2. Run the Jupyter Notebook file step-by-step to reproduce the analysis.
3. Modify parameters (e.g., cost thresholds, rating filters) to explore custom insights.

---

## Libraries Used
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

---

## Visualization Examples
Sample visualizations include:
- Restaurant type distribution.
- Total votes by restaurant type.
- Top restaurants for online and table bookings.
- Rating distribution histogram with mean and median indicators.

---

## Contact
For further questions or collaboration, please reach out to the project owner or contribute via pull requests.

