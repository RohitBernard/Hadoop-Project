# Hadoop-Project
Our project aims at mining a Social Media Dataset to find the connected users. Using the concept of MapReduce we try to solve this problem.When given a large dataset related to social media, it is really hard to find connected users, their interests, etc.
 
In this project, given a dataset (social media) can be used to find the connected users. The results can be further used to drive some promotion of ads, suggest friends or relevant events, etc.

## Instructions to compile:
Execute on CLI -  
set HADOOP_CLASSPATH=%JAVA_HOME%/lib/tools.jar  
hadoop com.sun.tools.javac.Main Graph.java  

move class files to edu/uta/cse6331/  

jar cvf g.jar edu/uta/cse6331/*.class  

## Instructions to run:
Upload input files to hdfs   
Create directory to store intermediate files   

hadoop jar g.jar edu/uta/cse6331/Graph /input_directory /intermediate /output
