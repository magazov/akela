# Akela #

Version: 0.3  

#### Mozilla's utility library for Hadoop, HBase, Pig, etc. ####

### Version Compatability ###
This code is built with the following assumptions.  You may get mixed results if you deviate from these versions.

* [Hadoop](http://hadoop.apache.org) 0.20.2+
* [HBase](http://hbase.apache.org) 0.90+
* [Pig](http://pig.apache.org) 0.9+
* [Hive](https://github.com/xstevens/hive) 0.7 with [automatic promotion of certain types](https://github.com/xstevens/hive/commit/566ca633546e5231cf5ea20d554c1f61784f39e4)

### Building ###
To make a jar you can do:  

`mvn package`

To make a Hadoop MapReduce job jar with no defined main class in the manifest:  

`mvn assembly:assembly`


### License ###
All aspects of this software written in Java are distributed under Apache Software License 2.0.

### Contributors ###

* Xavier Stevens ([@xstevens](http://twitter.com/xstevens))
* Daniel Einspanjer ([@deinspanjer](http://twitter/deinspanjer))