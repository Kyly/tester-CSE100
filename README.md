tester105
=========

This is my ever changing tester for CSE 105.

Installation
---
- Download the tester then make it a executable.
````
$ chmod +x tester
````
Where _tester_ will be replaced with version name your using.
- Bam! Your ready to test.

Running tester for PA2
---
- To run just type the tester name, file to compress, file to compress to,
and the file to uncompress to.
````
$ tester <to_compress> <compressed> <uncompress_to>
````
Running tester compiles then runs compress and uncompress then compares the two
file using `cmp`, if there are no errors from cmp then the final output will
be "Success".
