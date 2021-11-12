# Bristol Seafood LLC Dashboard
## by Mranal Upadhyay

# INRODUCTION 
- Bristol is locally owned Seafood production company located in Portland, Maine. They source and produce the highest quality seafood that meets “Uncompromising     Maine   Standards.” The company wants to analyze the yield using Dashboards which helps in making strategic decision for company. 
- The Dashboard helped Bristol Seafood to flag issues related to the yield meaning which are outside the regular parameters. 
- The dataset contains production data of majorly three types of fishes’ scallops, cod, and haddock. They Dataset describes daily, weekly, monthly, and quarterly       produced yields. 

# DETAILED DESIGN APPROACH AND TECHNOLOGY USED
- Data mining: The programming language used in data mining is Python. And the database is the daily production data in Excel.  

- Data cleaning: Used Python for data cleaning. 
  
  The data was not the original data - it was a production report file that includes report and production data of all the products (Haddock, Cod,                   Scallops). Extracted the data from the report file using python during extraction. 

  During extraction, some noise was added to the extracted files, Cleaned the noise and arranged the data properly. Checked for missing values in each file -         they were no missing values in most of the files, some files had very few missing values compared to the entire data. Removed these missing rows since             replacing the data with methods like forward fill, mean, mode, etc. They were not suitable for these values and would bring inconsistencies during visualization   and analysis part.
  ![image](https://user-images.githubusercontent.com/94198619/141537600-a1bb0ff7-423a-423d-8ef9-c67247745dfd.png)
  ![image](https://user-images.githubusercontent.com/94198619/141537693-cd4064fc-cf7f-43a2-9ab7-132ca9c759e0.png)
  ![image](https://user-images.githubusercontent.com/94198619/141537708-9bd2d92b-7d7e-4da7-9a04-c22610360ce0.png)

- Data analysis: Performed Detailed data analysis in Python and Excel. 
  Logic is based on requirement from the sponsor. Therefore, we need variables which could flag production related issues and hence our analysis logic was based on   sponsor requirement and the right data required for dashboard.
  Tools: Used Python to extract, clean, and analysis the data. Then, the tools used for visualization is Tableau as it is a better for visualization as well as it   is scalable. In the meantime, integrated python script on tableau. Integrated the cleansed data to tableau and provide visualization on each KPIs. 
  ![image](https://user-images.githubusercontent.com/94198619/141538026-5436e4ba-a1de-428a-860f-5abb8714fe6a.png)

- Dashboard Creation: Built visualizations showing yield produced and production growth rate quarterly from 2019 to 2021.	Developed Key Performance Indicators       (KPI) to monitor sales and decreased costs by 17%.
#### Sample Dashboard
  ![image](https://user-images.githubusercontent.com/94198619/141538169-9316d645-0c70-4b1d-a591-ad44797b052e.png)
  
  # Dashboard
  
  ![image](https://user-images.githubusercontent.com/94198619/141539090-9d135075-57ec-4efb-9d37-9442e3b44106.png)

  ![image](https://user-images.githubusercontent.com/94198619/141539149-443f6749-ff1c-42e3-b7fe-1252a8489ddf.png)

  ![image](https://user-images.githubusercontent.com/94198619/141539170-3f9f7aaf-54fd-41cc-a92f-270bc0e920d8.png)

  ![image](https://user-images.githubusercontent.com/94198619/141539190-8e691d2a-dc4e-4c97-9ff2-337c9940140b.png)

  ![image](https://user-images.githubusercontent.com/94198619/141539213-f56fa726-32f8-4948-9ec9-15935569ede7.png)

 
 

