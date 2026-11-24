# Readme (Sorting )

This package contains all source codes for 
1. Maximum Selection Sort

# Usage Step
1. Compilation
	```sh
    gcc sort.c -o sort
    ```

2. Execution
    ```sh
    ./sort
    ```

3. Input Files (Format of those files can be found in Appendix)
   1. we have file "config.txt" for configuration
   2. Dataset for sorting

4. Output Files (Format of those files can be found in Appendix)
   1. "output.txt" which contains the sorted data
   2. "time.txt" which captures the time statistics of the program
   3. "stat.txt" which captures the number of swapping of the sorting algorithm


## Appendix A. Format of Configure file (config.txt)

The file contains one line, with the following information separated by space.
1. [Dataset file name] (The data file name for sorting)
2. [Data size] (The number of elements in the dataset)
3. [Parameter 2] (Dummy value)
4. [Parameter 3] (Dummy value)
5. [Parameter 4] (Dummy value)

## Appendix B. Format of data file for sorting

The dataset file contains one line, containing the elements to be sorted,
separated by space.

## Appendix C. Format of "time.txt"

The output file contains one line, the sorted elements, separated by space.

## Appendix D. Format of "time.txt"

Each line corresponds to a user time and system time
1. time for reading the input data
2. time for sorting the data
3. time for writing the output data
9. time for all parts

## Appendix E. Format of "stat.txt"

The file contains one number only, which is the number of swapping of the sorting algorithm.