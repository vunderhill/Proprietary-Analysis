Increases in Trade Secret Claims in Hydraulic Fracturing Fluids and their Potential Implications for Environmental Health and Water Quality 
Journal of Environmental Management

Description: 
This project analyzes the masses of “proprietary” or “trade secret” claims from 2014-2022 using the open-source fracking chemical disclosure database Open-FF. 

How to access the data: 
 Please follow these links to the full dataset used for this paper (v 16 of Open-FF, downloaded as of August 31, 2023): 
  
  Pandas dataframe in parquet format: https://storage.googleapis.com/open-ff-common/repos/keep_proprietary_paper_data/full_df.parquet
  
  Raw download of the FracFocus data: https://storage.googleapis.com/open-ff-common/repos/keep_proprietary_paper_data/ff_archive_2023-07-26.zip

  Interactive maps of proprietary disclosures by county: https://storage.googleapis.com/open-ff-common/repos/keep_proprietary_paper_data/maps_of_proprietary_article.html
  


Warning: the Open-FF dataset is quite large, so storing it on a Cloud platform will be more space-efficient than on your personal computer. The notebook below reads the data directly from the cloud-stored files.

How to run the notebook: 
This page includes a Jupyter Notebook entitled “JEMA_FracFocus_proprietary_analysis.ipynb” that contains all of the Python code that generates statistics and visualizations used in this paper. It also includes a standalone HTML version of interactive maps showing proprietary disclosures and total disclosures per US county. 

(Note that this notebook enacts filtering and data cleaning in its first few lines. It drops all records that don’t have a CalcMass value, and removes one outlier that is two orders of magnitude larger than the rest of the dataset. It also filters to only include data from Jan 1, 2014 to December 31, 2022). 

Each step of the analysis has already been written into the notebook so you can run it in full or run only specific sections. 


Authors and Contributors: 
Holden Huntzinger and Gary Allison authored this code. Vivian Underhill wrote this ReadMe. 
