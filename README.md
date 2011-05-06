# Akela v0.1 #
A bunch of utility classes for Java, Hadoop, HBase, Pig, etc.


## Requirements ##
This code is built with the following assumptions.  You may get mixed results if you deviate from these versions.

[Hadoop](http://hadoop.apache.org) 0.20.2+  
[HBase](http://hbase.apache.org) 0.90+  
[Pig](http://pig.apache.org) 0.8+  


## Building ##
To make a jar you can do:  

`ant jar`

To make a Hadoop MapReduce job jar with no defined main class in the manifest:  

`ant hadoop-jar`


## License ##
All aspects of this software written in Java are distributed under Apache Software License 2.0.  
All aspects of this software written in Python are distributed under the [Mozilla Public License](http://www.mozilla.org/MPL/) MPL/LGPL/GPL tri-license.