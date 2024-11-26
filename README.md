# Final Project: Using Multilinear Regression of Publicly-Provided NAM Forecast Data to Develop Site-Specific Wind and Temperature Models
- Final Project
- Steph Abegg (I okayed it with James to do this project solo so I could use company data)

## Report

The entire project and results and conclusions are described in this report:

[Final_Project_Report.pdf](Final_Project_Report.pdf)

## Presentation

This is the powerpoint for the in-class presentation:

[Final_Project_Presentation.pptx](Final_Project_Presentation.pptx)

## Python Notebook Files

The following are the notebook files used to conduct the analysis:

[read_nam_files.ipynb](Python/read_nam_files.ipynb)
Reads in the NAM files from .tar files, extracts the desired wind and temperature forecasts for the location of the anemometer, and saves in .csv. 

[3d_vs_NAM_analysis.ipynb](Python/3d_vs_NAM_analysis.ipynb)
Compares the 3D anemometer measurements to the NAM forecast data over the same timeframe, via timeseries plots, histograms, binning, and linear regression.

[regression.ipynb](Python/regression.ipynb)
Develops a multilinear regression model trained on NAM forecast data to predict site-specific wind and temperature predictions. The model performance is also assessed.

## Project Requirements

My project meets the project requirements, detailed a follows: 

- My project is about a problem worth solving, analyzing, and visualizing. In fact, my (previous) company plans to implement the results.
- My project uses machine learning, since my project focuses on developing a multilinear regression model (regression is type of supervised learning method) to use forecast data to model site-specific conditions.
- My project uses Scikit-learn for the multilinear regression.
- My project dataset contains well over 100 records.
- From the list of "you must use at least two of the following", My project uses:
  - Python Pandas
  - Python Matplotlib
- Since my project is based on Python analysis, my project uses several other additional python packages/libraries, such as:
  - Python datetime
  - Python numpy
  - Python math
  - Python scipy.stats
  - Python pygrib
  - Python os
  - Python requests
  - Python bs4 BeautifulSoup
  - Python tarfile
