<h1 align="center">zomatoAnalyse</h1>


Creating a Data Analysis Project based on Zomato chain supply to promote food in need in those cities.
Creating a Python script that loads the Zomato dataset, cleans it, and performs exploratory data analysis (EDA) to extract valuable insights. 
<hr>
The script will cover:


<li>Loading and inspecting the dataset</li>
<li>Handling missing values</li>
<li>Data cleaning (renaming columns, removing duplicates)</li>
<li>Exploratory analysis (distribution of ratings, most popular cuisines, price range analysis, etc.)</li>
<br>



I've improved the accuracy of the analysis by:

<li>Converting relevant columns to numeric types.</li>
<li>Filtering out zero ratings to avoid misleading insights.</li>
<li>Extracting only the primary cuisine from the list.</li>
<li>Adding a correlation heatmap to analyze relationships.</li>

<hr>


<h1 align="center">Summary</h1>


The zomatoAnalyis Python script performs an exploratory data analysis (EDA) on the Zomato dataset to extract valuable insights. Below is a breakdown of its key steps:
<hr>


1. Data Loading and Inspection

<li>The script loads the Zomato dataset using Pandas.</li>
<li>It prints dataset information and the first few rows to understand the structure.</li>

<br>

2. Data Cleaning and Preprocessing
<li>Handles missing values by removing incomplete rows.</li>
<li>Standardizes column names by converting them to lowercase and replacing spaces with underscores.</li>
<li>Removes duplicate records to ensure data integrity.</li>
<li>Converts relevant columns (aggregate_rating and price_range) to numeric types for accurate analysis.</li>
<li>Filters out rows where the rating is zero to avoid skewed results.</li>

<br>

3. Exploratory Data Analysis (EDA) with Visualizations

<li>Rating Distribution: A histogram is used to visualize the distribution of aggregate ratings.</li>
<li>Most Popular Cuisines: Extracts the first cuisine type and displays the top 10 most frequent ones using a bar chart.</li>
<li>Price Range Analysis:</li>
<li>A count plot shows how restaurants are distributed across different price ranges.</li>
<li>A box plot compares aggregate ratings across different price ranges.</li>
<li>Correlation Heatmap: Displays the relationship between price range and aggregate ratings.</li>

<br>


4. Final Output

<li>The script prints the final message indicating the completion of the analysis.</li>
<li>Several plots are generated to provide insights into restaurant ratings, cuisine popularity, and pricing trends.</li>
