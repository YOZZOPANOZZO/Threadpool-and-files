# Threadpool-and-files

 Program that given a list of directories as input, compresses all the files in them, with the gzip utility.

Only zip the files contained in the directories passed as input, do not consider recursion on any soIttodirectories
The reference to each identified file is passed to a task, which must be executed in a threadpool. identify in the JAVA API the appropriate support class for compression
NOTE: The use of threadpools is indicated, because the tasks present a good mix of I/O and computation

● I/O heavy: all files must be read and written.

● CPU-intensive: compression requires a lot of computation

Optional: recursively compress Files in all subdirectories
