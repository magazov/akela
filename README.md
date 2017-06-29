# Akela #

Version: 0.7

#### Mozilla's utility library for Hadoop, HBase, Pig, etc. ####

### Version Compatability ###
This code has been tested with CDH5 (YARN, HBase 0.98+, Pig 0.12+).  You may get mixed results if you deviate from these versions.

### Building ###
To make a jar you can do:  

`mvn package`

To make a Hadoop MapReduce job jar with no defined main class in the manifest:  

`mvn assembly:assembly`


### License ###
All aspects of this software written in Java are distributed under Apache Software License 2.0.
