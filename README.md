# PySpark_setup_colab
This project is to show how to set up PySpark in Google Colab.
spark-2.4.5 has been used here to set up the environment at the time of this project.

If spark 2.4.5 is not available for download at the moment someone is setting up or 
if someone wants to setup a different version of spark using different download link then,
please update the following three details with the availble verion of spark and download link.

!wget -q http://apachemirror.wuchna.com/spark/spark-2.4.5/spark-2.4.5-bin-hadoop2.7.tgz

!tar xf spark-2.4.5-bin-hadoop2.7.tgz

os.environ["SPARK_HOME"] = "/content/spark-2.4.5-bin-hadoop2.7"
