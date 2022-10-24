# **Cryptocurrencies**

## Project Overview

### Executive Summary
A client, Accountability Accounting, has asked for a report that includes (1) the cryptocurrencies trading on the market and (2) grouped into a classification system from which the client can easily pick them and review their performance.
The following steps are employed in creating this report:
1. Preprocess data for unsupervised learning using Principal Component Analysis (PCA).
2. Reducing data dimensions using PCA 
3. Cluster the data using K-means and the elbow curve.
4. Visualizing cryptocurrencies results using a 3D model

### Data Sources
The data sources to complete this project are outlined below:<br>
* [crypto_data.csv](https://github.com/mrmarken/Cryptocurrencies/blob/main/Resources/crypto_data.csv)

### Software Used
Python 3.7.13
Jupyter Notebook:
IPython          : 7.31.1
ipykernel        : 6.9.1
ipywidgets       : 7.6.5
jupyter_client   : 6.1.12
jupyter_core     : 4.9.2
jupyter_server   : 1.13.5
jupyterlab       : 3.3.2
nbclient         : 0.5.13
nbconvert        : 6.4.4
nbformat         : 5.3.0
notebook         : 6.4.8
qtconsole        : 5.3.0
traitlets        : 5.1.1


## Results 
The following figures and associated descriptions provide an overview of the results of unsupervised machine learning tools used in this project:

| ![Figure1](https://github.com/mrmarken/Cryptocurrencies/blob/main/Resources/Images/01-Raw_data_df.png) |
| :---: |
| **Figure 1.** |

| ![Figure2](https://github.com/mrmarken/Cryptocurrencies/blob/main/Resources/Images/02-tradable_cryptocurrencies_df.png) |
| :---: |
| **Figure 2.** Tradable Cryptocurrencies DataFrame |

| ![Figure3](https://github.com/mrmarken/Cryptocurrencies/blob/main/Resources/Images/03-number_of_null_values.png) |
| :---: |
| **Figure 3.** Number of rows with null values: 459 |

| ![Figure4](https://github.com/mrmarken/Cryptocurrencies/blob/main/Resources/Images/04-Cleaned_df.png) |
| :---: |
| **Figure 4.** Cleaned DataFrame |

| ![Figure5](https://github.com/mrmarken/Cryptocurrencies/blob/main/Resources/Images/05-elbow_curve.png) |
| :---: |
| **Figure 5.** Elbow Curve confirms k=4 (4 clusters) |

| ![Figure6](https://github.com/mrmarken/Cryptocurrencies/blob/main/Resources/Images/06-Grouped_cryptocurrencies_df.png) |
| :---: |
| **Figure 6.** Cryptocurrencies grouped by 1 of 4 classifications |

| ![Figure7](https://github.com/mrmarken/Cryptocurrencies/blob/main/Resources/Images/07-3D-Scatter%20with%20Clusters.png) |
| :---: |
| **Figure 7.** 3D Scatter Plot with Clusters |

| ![Figure8](https://github.com/mrmarken/Cryptocurrencies/blob/main/Resources/Images/08-tradable_cryptocurrencies_table.png) |
| :---: |
| **Figure 8.** Tradable Cryptocurrencies Table |

| ![Figure9](https://github.com/mrmarken/Cryptocurrencies/blob/main/Resources/Images/09-tradable_cryptocurrencies_number.png) |
| :---: |
| **Figure 9.** Number of Tradable Cryptocurrencies |

| ![Figure10](https://github.com/mrmarken/Cryptocurrencies/blob/main/Resources/Images/10-hvplot_scatter_plot.png) |
| :---: |
| **Figure 10.** hvplot Scatter Plot |
