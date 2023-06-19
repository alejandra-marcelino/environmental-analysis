# Analyzing Climate Change Data

The purpose of this project is to use PySpark and data analysis techniques to investigate the phenomenon we know as “climate change”.

Environmental scientists continue to warn us about the consequences certain human activities, such as the combustion of fossil fuels, can have on the environment. In particular, researchers emphasize the long term changes these activities have on the weather and global climate. We often hear, to what seems like an increasing extent, about cases where temperatures have exceeded recorded highs, and about ongoing conditions that make it favorable for intense wildfires to occur. For example, the ongoing Canadian wildfires have already caused the most land damage compared to those of previous wildfire seasons. We ultimately want to see how the data translates to the trends commonly associated with climate change.

We use data on average monthly temperatures, data on CO2 emission levels, and data on climate events and natural disasters. Each dataset is converted to a PySpark DataFrame so that we can take advantage of the efficiency of using Spark for large datasets, along with the simplicity brought by the Python API, and access to SQL-like operations to help us transform and query our data. We also use some helpful libraries: sklearn (scikitlearn) to perform basic data analysis, and matplotlib, to visualize our data.
