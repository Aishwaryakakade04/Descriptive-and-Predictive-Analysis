
# Dash Application for Amazon Sales Data Analysis

## Overview

This Dash application provides an interactive interface for exploring Amazon sales data. Users can visualize data through scatter and bar charts, with options for customizing the displayed metrics and applying filters based on different categories.

## Features

- **Scatter and Bar Charts**: Visualize relationships between different metrics like `rating`, `rating_count`, and `actual_price`.
- **Dropdowns and Sliders**: Interactive components allow users to select variables for plotting and filter data.
- **Error Handling**: Basic setup for error handling in the application server.

## Prerequisites

Ensure you have the following Python packages installed:

- Dash
- Plotly
- Pandas
- Dash Core Components
- Dash Table

You can install these packages using pip:

bash
pip install dash plotly pandas dash-core-components dash-table


## Setup

1. **Clone the Repository**:

   bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   

2. **Install Dependencies**:

   bash
   pip install -r requirements.txt
   

   Make sure you have the `requirements.txt` file which includes all necessary packages.

3. **Prepare the Data**:

   Ensure that the `amazon.csv` file is placed in the `/content/` directory or update the file path in the script to point to the correct location of your CSV file.

## Application Structure

- **`app.py`**: The main script that defines the layout and callbacks for the Dash application.
- **`amazon.csv`**: The dataset used by the application containing sales data.

## Usage

1. **Run the Application**:

   bash
   python app.py
   

2. **Access the Application**:

   Open your web browser and navigate to `http://127.0.0.1:8050/` to interact with the application.

## Layout and Components

- **Header**: Displays the title of the application.
- **Data Table**: Shows a paginated table of the dataset.
- **Dropdowns**: Allow selection of variables for the x and y axes of charts.
- **Checklist**: Option to apply color encoding to charts.
- **Slider**: Filter data based on `actual_price`.
- **Graphs**: 
  - `scatter_plot`: Displays a scatter plot based on selected metrics.
  - `bar_chart`: Displays a bar chart based on selected metrics.

## Callbacks

- **`update_graph`**: Updates a line graph based on dropdown selection.
- **`update_chart`**: Updates the scatter plot based on dropdown and checklist selections.
- **`update_figure`**: Generates a scatter plot with specific filters applied.

## Error Handling

The application includes a basic error handler that can be customized to handle exceptions and display appropriate error messages.

## Contribution

Feel free to fork the repository and submit pull request.

## Contact

For any questions or feedback, please reach out to [Aishwarya kakade](aishwarya04kakade@gmail.com).

---
