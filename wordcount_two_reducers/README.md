# Hadoop MapReduce WordCount Practical

## Description
This project demonstrates a Hadoop MapReduce WordCount program to count the frequency of words in a text file.

## Files Included
- WordCount2.java (Java MapReduce code)
- dbzinput.txt (Sample input file)

## How to Run

### 1. Compile the Java Code
```bash
javac -cp $(hadoop classpath) WordCount2.java
jar cf wc.jar WordCount2*.class
hadoop fs -mkdir -p /user/pramathd2301/input
hadoop fs -put input/dbzinput.txt /user/pramathd2301/input/

hadoop jar wc.jar WordCount2 /user/pramathd2301/input/dbzinput.txt /user/pramathd2301/output.dbz/

hadoop fs -cat /user/pramathd2301/output.dbz/part-r-00000

