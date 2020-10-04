# Foundations and Growth of Functions #
Graphs the running times of insertion sort and merge sort algorithms that sort data from a text file in descending order.

## Files ##
***file_handler.py***: Wraps the reading/writing of code to text files into functions that can be called from outside of the file.

***algorithms.py***: Contains the functions for the insertion sort and merge sort algorithms.

***insertsort.py*** and ***mergesort.py***: These use the *file_handler.py* and *algorithms.py* functions to read data from the *data.txt* file, sort the data, and then write the data out to their respective *insert.out* and *merge.out* files.

## Instructions ##
**To run *mergesort.py* and *insertsort.py***:
1. The file *data.txt* needs to be in the same directory as *mergesort.py* and *insertsort.py*.
2. The *data.txt* file structure follows:
    1. First value of each line is the number of integers that need to be sorted, followed by the integers.
    2. Example values for *data.txt*:
        <pre>
        <code>4 19 2 5 11
        8 1 2 3 4 5 6 1 2</code></pre>
3. The output will be written to files called *merge.out* and *insert.out* in the same directory as *mergesort.py* and *insertsort.py*.

**To run *mergeTime.py* and *mergeSort.py***:
1. Run *mergeTime.py* and *mergeSort.py*.
2. Array size and runtime will be printed to the screen.
