# spark-first-example
This program gives very basic example of Apache Spark on local machine which you can execute without hadoop.

Pre-req 
Please check paths present in the file WordCount.java
String inputFile="/home/prakash/workspaces/First/spark-first-example/LICENSE";
 String outputFolder="/home/prakash/workspaces/First/output";

How to run this program 
mvn clean package exec:java [inputFile] [outputFolder]

Once program successfully executes, you will file named part0000 in output folder specified.
This file will contain the word count of all the words in that file.
