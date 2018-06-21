Usage:

-i Input filename

> python DCA.py -i file.txt

Output:

anti.dat: Line separated anti dictionary in ASCII
compressed.dat: First line represents the original size of the file in bits and the chars the compressed file in ASCII

Remarks:

Compression take a lot of time for files larger than 4KB due to Python's maximum recursion depth