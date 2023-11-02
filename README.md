# 💨🌏 Analysis of CO2 Production by Country

# Context:

In this project, we will delve into the analysis of CO2 emissions, categorized by country. The primary objective is to conduct a straightforward exploratory analysis of the data as a whole. This will enable us to familiarize ourselves with the practice of data exploration and address any practical challenges that may arise.

# Tools Used:

For this project, we will leverage the Python programming language, utilizing the json library.

# Project Data Set:

We have at our disposal a dataset detailing CO2 production broken down by country. Initially, we have limited information about this dataset. Hence, our foremost mission will be to thoroughly explore the dataset to gain an understanding of its structure.

The data is originally stored in a single file in JSON format.

# Conclusions

* Upon querying the 'data' field, it became evident that it comprises a dictionary, with each key containing a list.

* After examining the 'ISO 3166-1 alpha-3' key, we noticed redundant information, as we already had the 'Country' field. To enhance clarity, we decided to introduce a new column named 'Country_Code' with identical data.

* A comparison between the unique data in 'Country' and 'Country_Code' revealed discrepancies in length. Additionally, 'Country_Code' included various entries with '0' values, corresponding to historical entities like "French Equatorial Africa", "French West Africa", "Kuwaiti Oil Fires", "Leeward Islands", "Pacific Islands (Palau)", and "Ryukyu Islands".

* Exploration of the 'Year' key unveiled a list of consecutive years, ranging from 1750 to 2021. Further investigation confirmed that each country provides its own CO2 emissions measurements spanning from 1750 to 2021.

* Analysis of 'Total' data exposed a prevalence of zeros. This aligns with expectations, as it is improbable that comprehensive CO2 emission measurements were available for all countries dating back to 1750, especially considering geopolitical changes over time.

* Our dataset encompasses a total of 694,144 records, providing a substantial dataset for analysis.

* The project's initial objectives were successfully met. We have successfully addressed all posed questions, guided by the established criteria.

