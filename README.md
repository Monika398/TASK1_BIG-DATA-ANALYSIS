# TASK1_BIG-DATA-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS PRIVATE LIMITED

*NAME*: MONIKA ROUT

*INTERN ID*: CITS376

*DOMAIN*: DATA ANALYTICS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION OF TASK1*

# BIG DATA ANALYSIS USING PYSPARK

## Objective

The objective of this project is to perform big data analysis using PySpark on a large sales dataset and generate meaningful business insights from the data. The project focuses on understanding sales performance, customer trends, product categories, and regional revenue generation using scalable data processing techniques. PySpark was used because it can efficiently process large datasets and perform distributed computing operations much faster than traditional data analysis tools.

---

## Tools & Technologies Used

The following tools and technologies were used in this project:

* **Python:** Used as the primary programming language for data analysis and visualization.
* **PySpark:** Used for big data processing and handling large datasets efficiently.
* **Pandas:** Used for reading and preprocessing the dataset before converting it into a Spark DataFrame.
* **Matplotlib:** Used for creating charts and visualizing sales analysis results.
* **Google Colab:** Used as the development environment for executing the project online without local setup.

---

## Dataset Used

The project uses the **Superstore Sales Dataset**, which contains detailed sales transaction records of a retail company. The dataset includes multiple attributes such as:

* Order ID
* Customer Name
* Product Category
* Sales Amount
* Profit
* Region
* Ship Mode
* Order Date

This dataset helps in analyzing business performance, identifying profitable categories, and understanding regional sales distribution.

---

## Steps Performed

The following steps were performed during the execution of the project:

1. **Installed PySpark in Google Colab** using pip commands.
2. **Created a Spark Session** to initialize the PySpark environment.
3. **Loaded the dataset using Pandas** from a CSV file.
4. **Converted the Pandas DataFrame into a Spark DataFrame** for big data processing.
5. **Displayed the dataset and schema** to understand the structure and data types.
6. **Counted the total number of rows** present in the dataset.
7. **Performed category-wise sales analysis** to identify the highest-selling product category.
8. **Performed region-wise sales analysis** to determine which region generated maximum revenue.
9. **Used aggregation functions** such as groupBy() and sum() for data analysis.
10. **Generated visualizations using Matplotlib** to present the analysis results in graphical form.

---

## Output Summary

The analysis produced several important business insights:

* Total rows processed in the dataset: **9994**
* The **Technology** category generated the highest sales among all product categories.
* The **West** region contributed the highest overall revenue.
* Sales trends and category performance were successfully visualized using charts and graphs.
* PySpark efficiently handled the dataset and completed analysis tasks successfully.

---

## Conclusion

This project successfully demonstrated the implementation of big data analysis using PySpark. The dataset was processed efficiently using Spark DataFrames, and meaningful insights were generated through category-wise and region-wise analysis. The use of PySpark helped in understanding how large-scale data can be analyzed quickly and effectively. Visualization techniques further improved the understanding of sales trends and business performance. Overall, this project provided practical experience in big data technologies, data processing, and business analytics using Python and PySpark.


