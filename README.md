# spark-first-example
This program runs very basic example of Apache Spark on local machine and counts words in the given file.
Output of the program is stored in the directory provided.

Pre-requisite:

Please check paths present in the WordCount.java file. Modify paths if necessary and if you dont want to provide them on command line.
String inputFile="/home/prakash/workspaces/First/spark-first-example/LICENSE";
String outputFolder="/home/prakash/workspaces/First/output";


How to run this program 
mvn clean package exec:java [inputFile] [outputFolder]

Once program successfully executes, you will file named part0000 in output folder specified.
This file will contain the word count of all the words in that file.
