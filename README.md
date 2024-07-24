# airline-ticket-booking-analysis
This project analyzes airline ticket booking data to extract insights and visualize various aspects such as summary statistics, distribution analysis, categorical analysis, clustering, route popularity, and the impact of stops.
## Data
The dataset includes the following features:
- `airline`
- `flight`
- `source_city`
- `departure_time`
- `stops`
- `arrival_time`
- `destination_city`
- `class`
- `duration`
- `days_left`
- `price`
## Usage
### Jupyter Notebooks

You can explore the analysis in the Jupyter notebooks located in the `notebooks/` directory.
## Project Overview

This project focuses on analyzing airline ticket booking data to extract valuable insights. The analysis is structured into the following key components:

### 1. Data Preparation
- **Objective**: Clean and preprocess the dataset to ensure it is ready for analysis.
- **Tasks**:
  - Handle missing values and outliers.
  - Convert data types as needed.
  - Create new features and refine existing ones.

### 2. Exploratory Data Analysis (EDA)
- **Objective**: Explore the dataset to understand its structure and key characteristics.
- **Tasks**:
  - Generate summary statistics for numerical features.
  - Analyze distributions and identify potential outliers.
  - Examine relationships between categorical and numerical features.

### 3. Visualization
- **Objective**: Create visual representations to identify patterns and insights in the data.
- **Tasks**:
  - Use histograms, box plots, scatter plots, and bar charts.
  - Visualize distributions of numerical features.
  - Explore relationships between different features through plots.

### 4. Time-Based Analysis
- **Objective**: Analyze how booking data varies over time.
- **Tasks**:
  - Investigate time-based patterns in booking data.
  - Analyze price fluctuations and booking trends across different times of day.

### 5. Correlation Analysis
- **Objective**: Understand the relationships between numerical features.
- **Tasks**:
  - Compute the correlation matrix to identify strong relationships.
  - Visualize correlations using heatmaps.

### 6. Route Analysis
- **Objective**: Determine the most popular routes based on booking frequency.
- **Tasks**:
  - Count the number of bookings between each `source_city` and `destination_city`.
  - Identify and analyze the most frequently booked routes.


