# GES DISC Tutorials

A place to find cloud relevant tutorials on how to use GES DISC tools, services, and data.

Most tutorials in this repository take the form of python notebooks. Jupyter is a very popular version of python notebooks, and is used extensively by the GES DISC team.

| Notebook  | Summary | Services and Tools |
| ------------- |-------------|:-------------:|
| [How to Read IMERG Data Using Python ](notebooks/How_to_Read_IMERG_Data_Using_Python.ipynb)| This notebook shows how to read data from the Global Precipitation Measurement (GPM) mission's IMERG dataset using Python. |  |
| [How to Access MERRA2 Using OPeNDAP with Python3 and Calculate Weekly from Hourly Data ](notebooks/How_to_Access_MERRA2_Using_OPeNDAP_with_Python3_Calculate_Weekly_from_Hourly.ipynb) | This notebook is based on Python3 and demonstrates how to remotely access the Modern-Era Retrospective analysis for Research and Applications, Version 2 (MERRA-2) hourly files via OPeNDAP and analyze data such as resample hourly files into daily, weekly, and monthly files and calculate their corresponding statistics, e.g., mean, sum, maximum, and minimum. |
|[How to use the Web Services API for Dataset Searching ](notebooks/How_to_Use_the_Web_Services_API_for_Dataset_Searching.ipynb) | This example code demonstrates how to use the API to search GES DISC data collections.  |
|[How to Use the Web Services API for Subsetting MERRA-2 Data](notebooks/How_to_Use_the_Web_Services_API_for_Subsetting_MERRA-2_Data.ipynb) | The example code provided below demonstrates three examples on how to use the API to submit an asynchronous request to the GES DISC Subsetting Service in order to obtain subsets of the Modern-Era Retropsective analysis for Research and Applications, Version 2 (MERRA-2). |
|[How to Access GES DISC Data Using Python](notebooks/How_to_Access_GES_DISC_Data_Using_Python.ipynb) | There are multiple ways to work with GES DISC data resources using Python. For example, the data can accessed using techniques that rely on a native Python code. Still, there are several third-party libraries that can further simplify the access. In the sections below, we describe three techniques that make use of Requests, Pydap, and Xarray libraries. |
|[How to Directly Access MERRA-2 Data from an S3 Bucket with Python](notebooks/How_to_Directly_Access_MERRA-2_Data_from_an_S3_Bucket.ipynb) | This notebook demonstrates how to access and plot a Modern-Era Retrospective analysis for Research and Applications (MERRA-2) M2T1NXSLV.5.12.4 file hosted via an Amazon S3 bucket. It demonstrates how to access an S3 bucket with the S3FS library and then plot sea-level pressure contours of a single file with Cartopy and Matplotlib.|
