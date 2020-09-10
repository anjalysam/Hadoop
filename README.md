# Hadoop
### This contain how to install hadoop on google colab and how to run mapreduce in hadoop.

## 1. Hadoop_install.ipynb
#### This file contain hadoop installation on google colab.
steps in hadoop installation:
* 1.Installing hadoop using this link : https://downloads.apache.org/hadoop/common/hadoop-3.3.0/hadoop-3.3.0.tar.gz
* 2.Configuring Hadoop’s Java Home : Hadoop requires that you set the path to Java, either as an environment variable or in the Hadoop configuration file.
* 3.Running Hadoop
## 2. map_reduce.ipynb
upload mapper.py and reducer.py 
   ### mapper.py
   It will read data from *STDIN, split it into words and output a list of lines mapping words to their counts to *STDOUT.

   ### reducer.py
   It will read the results of mapper.py from STDIN  and sum the occurrences of each word to a final count, and then output its results to STDOUT.
