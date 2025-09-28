Hotel Bookings Analysis 🏨📊

This project analyzes the Hotel Bookings Dataset to uncover insights about booking trends, customer behavior, cancellations, and hotel popularity.
The analysis was performed using Python, Pandas, Matplotlib, and Seaborn.

📂 Project Structure
├── hotel_bookings.csv      # Dataset
├── Untitled16.ipynb        # Jupyter/Colab notebook with analysis
├── README.md               # Project documentation

⚙️ Setup & Installation

Clone this repository:

git clone https://github.com/your-username/hotel-bookings-analysis.git
cd hotel-bookings-analysis


Install dependencies:

pip install pandas numpy matplotlib seaborn


Open the notebook:

jupyter notebook Untitled16.ipynb


Or upload it to Google Colab.

📊 Key Steps in Analysis

Data Cleaning

Filled missing values in children and country

Dropped rows with missing agent and company

Removed duplicates

Feature Engineering

Created total_guests (adults + children + babies)

Created stay_duration (weekend + weekday nights)

Extracted booking_month

Visualizations

Monthly booking trends

Distribution of total guests

Resort popularity

Cancellation rates

Average stay duration per hotel type

📈 Sample Insights

Most bookings occur in summer months (July–August).

Majority of bookings are for Resort Hotels.

Cancellation rates are relatively high (~30–40%).

Families with children usually stay longer compared to solo travelers.

🛠️ Tools & Libraries

Python 3.9+

Pandas – data manipulation

NumPy – numerical operations

Matplotlib & Seaborn – data visualization

🚀 Future Improvements

Add machine learning models for cancellation prediction.

Perform time series forecasting for booking trends.

Deploy an interactive dashboard using Streamlit/Plotly.
