# MapReduce Logfile Analysis

This project performs word count on a large log file using Hadoop MapReduce.

## Structure

- `wordcount`: Word count with single reducer
- `wordcount_no_reducer`: Word count with no reducer
- `wordcount_two_reducers`: Word count with two reducers

## How to Run

1. Place your input file in HDFS.
2. Run the MapReduce job using the provided jar files.
3. The output will be stored in the specified HDFS directory.

## Note:
The large input file `logfiles.txt` is excluded from this repository to avoid exceeding GitHub's file size limit.
