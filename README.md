# San Francisco Rental Housing Market Analysis

This analysis looks at the number of housing units, sale price per square foot, and gross rent for the San Francisco Rental Housing Market to determine its suitability for piloting a one-click, buy-and-rent service.

## Technologies

This analysis leverages python 3.7 with the following packages:

- [numpy](https://numpy.org/) - For numerical operations  
- [pandas](https://pandas.pydata.org/) - For analyzing and transforming data  
- [pyviz](https://pyviz.org/) - For visualizing data 
- [holoviews](http://holoviews.org/) - For creating interactive plots
- [geoviews](https://geoviews.org/) - For visualizing geospatial data
- [jupyter](https://jupyter.org/) - For an IDE

## Installation Guide

Clone the repository and confirm that python 3.7 or greater and the packages listed in the Technologies section are installed.

```python
pip install numpy
pip install pandas
pip install pyviz
pip install hvplot
pip install geoviews
pip install jupyterlab
```

## Usage

Because the analysis leverages HoloViews the plots do not render when viewed from GitHub. To view the analysis and interact with the plots clone the repository and after ensuring all required packages have been installed run `jupyter lab` from the directory where the notebook is stored.

For a snapshot of the analysis images of the plots have been provided. In bold above the plot image is the cell output that it is associated within `san_francisco_housing.ipynb`

**Out[4]:**
![San Francisco Housing Units](Images/sf_housing_units.png)  

**Out[8]:**
![San Francisco Sale Price per Square Foot & Gross Rent](Images/sf_sale_prices_and_gross_rent.png)  

**Out[11]:**
![San Francisco Sale Price per Square Foot & Gross Rent Grouped by Neighborhood](Images/sf_sales_prices_gross_rent_by_neighborhood.png)  

**Out[17]:**
![San Francisco Neighborhoods by Sale Price per Square Foot and Gross Rent](Images/sf_neighborhoods_by_sales_price_and_gross_rent.png)  

**Out[19]:**
![San Francisco Annual Growth Rates of Sales per Square Foot and Gross Rent by Neighborhood](Images/sf_annl_growth_in_sale_price_and_gross_rent_by_neighborhood.png)

## Contributors

Josh Mischung: [josh@knoasis.io](josh@knoasis.io), [LinkedIn](https://www.linkedin.com/in/joshmischung/)

## License

MIT License

Copyright (c) [2022] [Joshua Mischung]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
