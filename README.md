# PySpark-GraphFrames
## Implementation of GraphFrames using PySpark in Eclipse Oxygen IDE

### 1. Installation Steps:
  a. Apache Spark vesrion: 2.4.0: Download Apache Spark from spark website and extract thrice using "7-Zip"
     Final Folder Structure will be: D:/Spark/spark-2.4.0-bin-hadoop2.7
     
  b. Download Scala 2.11.8 windows .msi file from Scala website
  
  c. Download Java 8, Python 3.7.2, PyDev 6.4.3 and winutils-master (GitHub URL: https://github.com/steveloughran/winutils)
      * PyDev is a plugin that enables Eclipse to be used as a Python IDE.
      * winutils-master: It is hadoop flavor on top of windows.
      * Hadoop final folder structure: D:\hadoop-2.7.1
          *bin, README.md,winutils (copy winutils.exe here after extracting using "7-Zip") 
          
  d.  Go to extracted folder for PyDev 6.4.3--->Go to plugins--->Copy all plugins and paste it into---> Eclipse--->Plugins
      Also, PyDev 6.4.3 features--->copy all features from PyDev and paste in Eclipse features folder.
      
  e. Eclipse Oxygen IDE environment variables setup:
       * HADOOP_HOME – path of the folder where winutils.exe is present
       * IP_HOME – IP of the system 
       * SPARK_CONF – go to final extracted folder spark--->conf and paste the path in value
       * SPARK_HOME – path of spark folder (final extracted folder)
       
  f. Add GraphaFrames 0.7.0 jar inside the spark-2.4.0-bin-hadoop2.7 jars
  
### 2. Setup System Variables:
  a. HADOOP_HOME
  
  b. JAVA_HOME
  
  c. SCALA_HOME
  
  d. PYSPARK_PYTHON
  
  e. SPARK_HOME
  
  f. %SPARK_HOME%\bin to Path variables(editing the System variable Path)
  
  g. PYSPARK_DRIVER_PYTHON = C:\Users\user\Anaconda3\envs\Scripts\jupyter.exe
  
  h. PYSPARK_DRIVER_PYTHON_OPTS = notebook
  
### * g. and h. in-case of using Jupyter Notebook, using Anaconda Navigator.
