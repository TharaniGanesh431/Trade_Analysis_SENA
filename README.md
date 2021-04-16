# Trade_Analysis_SENA
# Problem Statement:

  In modern society, Goods can be traded from one country to another through transportation. A country’s economy depends highly on trade. So the analysis of the data on trade plays a crucial role to understand world trade. It also provides insight into the country’s production performance and its significance in the world. 
This project aims to visualise and analyse the international imports and exports between the year 2013 to 2019. It also ranks countries based on the import and export of various products.  
Visualising the connectedness of the countries through import and exports as graphs provides a better vision on understanding world trade.

# Dataset Description:
  The dataset for this project is obtained from the world trade organisation [1] in CSV format 29131 rows and 8 columns. It contains information about countries involved in the import and export of various products along with the products that they import or export. This data is noted for the year between 2013 - 2019. The data contains the transactions (in US$) through the exports and imports of products for each year between 2013-2019.  

# Tools Used:
The tools used for visualisation and analysis of data are:
Pandas - for pre-processing of data from CSV file.
	Pandas is a fast, powerful, flexible and easy to use open-source data analysis and manipulation tool, built on top of the Python programming language.

Pyvis  - for construction and visualization of the graph.
	The pyvis library is meant for the quick generation of visual network graphs with minimal python code. It is designed as a wrapper around the popular Javascript visJS library.

NetworkX  - formed a graph for triadic closure.
	NetworkX is a Python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks.
	
# Challenges Faced:

1.Since the number of nodes (countries) in the dataset is large, the graph looks congested so nodes need to be scaled.  
2.Since there is no inbuilt function in pyvis to traverse the graph, the user-defined function needs to be explicitly for traversing.  
3.Since the dataset is huge, the CPU required more time for the processing which delayed the progress.
4.Limited documentation is available for pyvis library.
