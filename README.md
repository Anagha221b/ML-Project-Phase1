# ML-Project-Phase1

Columms and their description:

customer_id: Unique identifier for each customer.

region: Geographic region of the customer.

energy_consumption_kwh: Total energy consumption in kilowatt-hours.

peak_hours_usage: Energy usage during peak hours.

off_peak_usage: Energy usage during off-peak hours.

renewable_energy_pct: Percentage of energy from renewable sources.

billing_amount: Total billing amount.

household_size: Number of people in the household.

temperature_avg: Average temperature.

income_bracket: Income bracket of the household.

smart_meter_installed: Whether a smart meter is installed.

time_of_day_pricing: Whether time-of-day pricing is used.

annual_energy_trend: Annual trend in energy consumption.

solar_panel: Whether solar panels are installed.

target_high_usage: Whether the household is targeted for high usage.

Manipulations performed on dataset:

Loading the Dataset: The dataset is loaded from a CSV file.

Displaying Initial Shape: The shape of the dataset is displayed before any manipulations.

Removing Outliers: Outliers are removed from specified columns using the Interquartile Range (IQR) method.

Displaying Final Shape: The shape of the dataset is displayed after outlier removal.

Displaying Data Types: The data types of the features are displayed using the .info() method.

Visualizing Data:

Histograms: Histograms of numerical features are plotted to show their distributions.

Boxplot: A boxplot is created to visualize the presence of outliers in numerical features.

Pairplot: Pairwise relationships between numerical features are visualized using a pairplot.

Heatmap: A heatmap is generated to show the correlation between different numerical features.

Additional Visualizations:

Total Energy Consumption by Region: A bar plot showing total energy consumption by region.

Average Renewable Energy Percentage by Region: A bar plot showing the average renewable energy percentage by region.

Average Billing Amount by Income Bracket: A bar plot showing the average billing amount by income bracket.

Household Size Distribution: A bar plot showing the distribution of household sizes.

Smart Meter Installation by Region: A bar plot showing the number of smart meters installed by region.

Time of Day Pricing Adoption by Region: A bar plot showing the number of households with time-of-day pricing by region.
