# Create Pie Chart

This Python script, named `Create Pie Chart.py`, generates a pie chart using the `matplotlib.pyplot` library. The pie chart illustrates the distribution of marks in different subjects for a student named Jenani.

## Usage
1. Ensure you have Python installed on your system.
2. Install the necessary libraries. You can install `matplotlib` using pip if you haven't already installed it:
   pip install matplotlib
   
4. Run the script by executing the Python file `Create Pie Chart.py`.

## Description
- The script utilizes `matplotlib.pyplot` to create a pie chart.
- The `query` list contains the names of the subjects: 'Tamil', 'Maths', 'Science', 'English', and 'History'.
- The `values` list holds the marks obtained by Jenani in each subject, corresponding to the order in the `query` list.
- The `exp` list defines whether any slices of the pie chart are to be exploded for emphasis. Adjust the values in `exp` to control which slices are exploded.
- The `k.pie()` function generates the pie chart using the provided data.
- Labels for each slice are set using the `labels` parameter.
- The `autopct` parameter determines the format for displaying the percentages on the chart.
- `startangle` sets the angle at which the first slice begins.
- `explode` specifies the fraction of the radius with which to offset each wedge.
- Finally, `k.show()` displays the pie chart with the specified configurations.

Feel free to modify the data in the `query`, `values`, and `exp` lists to visualize different datasets.

**Note**: Make sure you have the appropriate permissions to display the chart if you are running this script in a non-interactive environment.
