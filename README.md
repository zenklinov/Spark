# PySpark on Google Colab Demo  
*A practical example of using Apache Spark with PySpark in Google Colab*

## Description  
This repository demonstrates how to set up and run PySpark in Google Colab, including a sample notebook and visualization. Modified from the [IBM Machine Learning Capstone template](https://colab.research.google.com/drive/1G894WS7ltIUTusWWmsCnF_zQhQqZCDOc), it provides:  
- Preconfigured Colab environment  
- Example data processing workflows  
- Integration with Spark's DataFrame API  

## Features  
✅ Preconfigured Colab setup  
✅ Sample notebook with code explanations (`MYColab_and_PySpark.ipynb`)  
✅ Spark UI visualization screenshot (`sparkcolab.png`)  

## Usage  
1. Open the [modified Colab notebook](https://colab.research.google.com/drive/1G894WS7ltIUTusWWmsCnF_zQhQqZCDOc)  
2. Run cells sequentially to:  
   ```python
   # Example Spark installation code
   !apt-get install openjdk-8-jdk-headless -qq > /dev/null
   !wget -q https://downloads.apache.org/spark/spark-3.3.0/spark-3.3.0-bin-hadoop3.tgz
   !tar xf spark-3.3.0-bin-hadoop3.tgz

## Requirements
Google account (for Colab access)
Basic Python knowledge
