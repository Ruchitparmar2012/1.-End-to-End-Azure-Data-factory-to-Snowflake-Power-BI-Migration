![image](https://www.linkpicture.com/q/Artboard-14x-14-1.png)


# End to End Azure  Data factory to Snowflake & Power BI Migration

This project aims to establish a seamless data integration pipeline that extracts data from an Azure Data Blob in JSON format, converts it into CSV format, loads it into Snowflake, and finally connects Snowflake to Power BI for visualization on a dashboard. 

The integration process ensures data flow from the Azure Data Blob to Power BI, enabling insightful data visualization and analysis.



## Table of Contents

- [Project Overview](#ProjectOverview)

- [Project Components](#ProjectComponents)

- [Project Setup and Execution](#ProjectSetupandExecution)

- [Conclusion](#Conclusion)


## Project Overview

The project involves the following key steps:

1. **Data Extraction**: The JSON file stored in an Azure Data Blob is the source of the data. The pipeline will extract the JSON data using Azure Data Factory.

2. **Data Conversion**: Using Azure Data Factory, the JSON data will be transformed into CSV format. This transformation is crucial for efficient data processing and compatibility with downstream systems.

3. **Data Loading into Snowflake**: Azure Data Factory will load the converted CSV data into Snowflake, a cloud-based data warehouse. Snowflake provides a powerful and scalable environment for storing and querying structured and semi-structured data.

4. **Data Visualization with Power BI**: After loading the data into Snowflake, Power BI will establish a connection to Snowflake to access the dataset. Using Power BI, users can create interactive visualizations, dashboards, and reports for data analysis and decision-making.

### Project Components

The project comprises the following components:

1. **Azure Data Blob**: The initial data source, where the JSON file is stored. It acts as the entry point for the data integration pipeline.

2. **Azure Data Factory**: Responsible for orchestrating the data integration process. It includes activities to extract data from the Azure Data Blob, convert it to CSV format, and load it into Snowflake.

3. **Snowflake**: A cloud-based data warehouse that provides storage and processing capabilities for structured and semi-structured data. Snowflake stores the transformed CSV data.

4. **Power BI**: Connects to Snowflake to access the data and facilitates the creation of interactive visualizations, reports, and dashboards. Power BI enables data exploration and insights generation.

### Project Setup and Execution

To set up and execute the project, follow these steps:

1. **Configure Azure Data Factory**: Set up Azure Data Factory with the necessary linked services for Azure Data Blob, Snowflake, and Power BI. Define the data pipelines, including activities for data extraction, conversion, and loading.

2. **Transform JSON to CSV**: Configure the data transformation process within Azure Data Factory to convert the JSON data from the Azure Data Blob into CSV format.

3. **Load Data into Snowflake**: Define the data loading process within Azure Data Factory to load the transformed CSV data into Snowflake. Ensure proper mapping and schema alignment.

4. **Connect Snowflake to Power BI**: Establish a connection between Snowflake and Power BI to access the data stored in Snowflake. Configure the necessary connection settings within Power BI.

5. **Create Power BI Visualizations**: Utilize the Power BI interface to design and develop interactive visualizations, reports, and dashboards based on the data loaded from Snowflake.

6. **Publish and Share**: Publish the Power BI dashboard and share it with the intended audience for data analysis and decision-making.

### Conclusion

This project showcases an end-to-end data integration and visualization pipeline, starting from an Azure Data Blob, transforming the data, loading it into Snowflake, and visualizing it in Power BI. By following the outlined steps, you can establish a robust data-driven solution that facilitates data exploration, analysis, and reporting for enhanced business insights.

For detailed implementation instructions and further customization options, please refer to the project documentation available in the repository's README on GitHub.

