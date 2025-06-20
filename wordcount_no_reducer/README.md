# Hadoop MapReduce - WordCount (No Reducer)

## Description
This project demonstrates a MapReduce job with **zero reducer** to process words and filter based on word length.

## Files:
- WordCountNoReducer.java
- wc_no_reducer.jar
- dbzinput.txt
- commands.txt

## Command to Run:
hadoop jar wc_no_reducer.jar WordCountNoReducer /user/pramathd2301/input/dbzinput.txt /user/pramathd2301/output_no_reducer -D mapreduce.job.reduces=0
