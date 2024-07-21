# Foundations and Growth of Functions #

Graphs the running times of insertion sort and merge sort algorithms that sort data from a text file in descending order. Homework assignment from CS325 – Analysis of Algorithms at Oregon State University.

## Files ##

```mergesort.py``` and ```insertsort.py```: These use the necessary functions to read data from the ```data.txt``` file, sort the data, and then write the data out to their respective *insert.out* and *merge.out* files.

```mergeTime.py``` and ```insertTime.py```: Uses the system clock to record the running times of each algorithm for n = 5000, 10000, 15000, 20,000, …. Then outputs the array size n and time to the terminal.

## Instructions ##
**To run ```mergesort.py``` and ```insertsort.py```**:
1. The file ```sata.txt``` needs to be in the same directory as ```mergesort.py``` and ```insertsort.py```.
2. The ```data.txt``` file structure follows:
    1. First value of each line is the number of integers that need to be sorted, followed by the integers.
    2. Example values for ```data.txt```:
        <pre>
        <code>4 19 2 5 11
        8 1 2 3 4 5 6 1 2</code></pre>
3. The output will be written to files called ```merge.out``` and ```insert.out``` in the same directory as ```mergesort.py``` and ```insertsort.py```.

**To run ```mergeTime.py``` and ```insertTime.py```**:
1. Run ```mergeTime.py``` and ```insertTime.py```.
2. Array size and runtime will be printed to the screen.
