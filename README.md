# modelaccuracymeasures
Java command line utility to calculate the various accuracy measures for a predictive model.
The utility takes an input csv file in the following format. The first line is the header line.

inst#	actual	predicted \
1	11308	8516.788 \
2	14816	11967.605 \
3	5399	5324.529

The utility takes the following input \
-i <fully qualified path of the input file> \
-o <fully qualified path of the output file>
