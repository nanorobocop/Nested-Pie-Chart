# Nested Pie Chart

Also known as:
* Multi-layer pie chart
* Multi-level pie chart
* Concentric pie chart
* Donut pie chart
* Pie chart with subcategories

![screenshot](screenshot.png "Screenshot")

## Description

* Use few Jupyter cells to beautifully visualize your data
* Data is taken from pandas dataframe
* Layers of pie chart are separate columns in dataframe
* You can specify layers of your pie chart from inner to outer
* Layers could have same keys between upper-layers, like same city could be in different category (this is handled by pandas.DataFrame.groupby)

## Usage

* Define your pandas dataframe as df
* Define variables:
  * `layers` is an list of pie chart layers from the inner to outer, example: `layers = ['company_type', 'state', 'city']`
  * `value` is column that will be interpreted as value to visualize (in simple case it could be just value 1)
* Execute and get your beautiful Nested Pie Chart!

