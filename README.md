# Data mining assignment 7

To run the attached text classification code, save the attached R file and a copy of the reutersCSV.csv
download into the same folder. Open the R file and set the R session's working directory to the source file 
directory.

Libraries required by the code are listed at the beginning of the file; make sure all of these are downloaded 
and installed before running the code.

Library RWeka requires RJava to run, which can cause a known error if R cannot find the path to the correct 
version of Java. I solved this problem by downloading and reinstalling the correct version of Java (at time 
of writing, the Java 64-bit offline download was the only one available that worked).

RWeka is only required for the bigram tokenizer, which wasn't used in the final version of the report but has 
been included for completeness here. If RWeka still won't install, just skip this package.

The remaining code can simply be run in order.
