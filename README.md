# Scalable-Machine-Learning-on-Big-Data-using-Apache-Spark

## To use pyspark in colab the following commands who make it possible

 !pip install pyspark
 import pyspark
 from pyspark import SparkContext,SparkConf
 from pyspark.sql import SparkSession
 sc=SparkContext.getOrCreate(SparkConf().setMaster("local[*]"))
