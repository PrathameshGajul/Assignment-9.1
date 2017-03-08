Q1.Why MapReduce program is needed in Pig Programming?
Ans:
-Pig raises the level of abstraction for processing large datasets.
-MapReduce allows the programmer to specify a map function followed by a reduce function.
-Pig is made up of two pieces:
1)The language used to express data flows, called Pig Latin.
2)The execution environment to run Pig Latin programs. There are currently two environments: local execution in a single JVM and distributed execution on a Hadoop cluster.
-A Pig Latin program is made up of a series of operations, or transformations, that are applied to the input data to produce output.
-Pig turns the transformations into a series of MapReduce jobs, but as a programmer we are mostly unaware of this, which allows
you to focus on the data rather than the nature of the execution.
-Pig is a scripting language for exploring large datasets.
-Pig isn’t suitable for all data processing tasks.
-MapReduce, it is designed for batch processing of data.
-If we want to perform a query that touches only a small amount of data in a large dataset, then Pig will not perform well, since it is set up to scan the whole dataset, or at least large portions of it.
-Pig doesn’t perform as well as programs written in MapReduce.
-It’s fair to say that unless you are willing to invest a lot of effort optimizing Java MapReduce code, writing queries in Pig Latin will save you time.


Q2.What are advantages of pig over MapReduce?
Ans:
The advantages of pig over Mapreduce are:
1)1/20 lines of code are needed than that map reduce.
2)People of non-programming background can also use pig easily.
3)Map reduce takes more time to construct the code.
4)Less complex codes to type.
5)Many built in functions.
6)Easy to learn pig latin than that of Java.


Q3.What is pig engine and what is its importance?
Ans:
-To write data analysis programs, Pig provides a high-level language known as Pig Latin.
-This language provides various operators using which programmers can develop their own functions for reading, writing, and processing data.
-To analyze data using Apache Pig, programmers need to write scripts using Pig Latin language.
-All these scripts are internally converted to Map and Reduce tasks.
-Apache Pig has a component known as Pig Engine that accepts the Pig Latin scripts as input and converts those scripts into MapReduce jobs.

Importance of Pig engine:
-It acts as interpreter between Pig latin scripts and Mapreduce jobs.
-It creates an environment to execute pig scripts into series of mapreduce jobs in parallel manner.


Q4.What are the modes of Pig execution?
Ans:
-Pig has two execution types :
1)Local Mode
2)Mapreduce Mode

Local Mode:
-In this mode, all the files are installed and run from your local host and local file system.
-There is no need of Hadoop or HDFS.
-This mode is generally used for testing purpose.

Mapreduce Mode:
-MapReduce mode is where we load or process the data that exists in the Hadoop File System (HDFS) using Apache Pig.
-In this mode, whenever we execute the Pig Latin statements to process the data, a MapReduce job is invoked in the back-end to perform a particular operation on the data that exists in the HDFS.


Q5.What is grunt shell in Pig?
Ans:
-Through Grunt shell,one can communicate with the pig engine.
-The Grunt shell of Apache Pig is mainly used to write Pig Latin scripts.
-After invoking the Grunt shell, you can run your Pig scripts in the shell.
-There are certain useful shell and utility commands provided by the Grunt shell.


Q6.What are the features of Pig Latin language?
Ans:
1)Easy to learn
2)Programs are less complex as compared to mapreduce
3)More built in functions
4)Less lines of code


Q7.Is Pig latin commands case sensitive?
Ans:
-Pig Latin has mixed rules on case sensitivity.
-Operators and commands are not casesensitive
-Aliases and function names are case-sensitive.


Q8.What is a data flow language?
Ans:
-To access the external data,every language must follow many rules and regulations.
-The instructions are flowing through data by executing different control statements,but data doesn't get moved.
-Dataflow language can get a stream of data which passes from one instruction to another instruction to be processed.
-Pig can easily process those conditions,jumps,loops and process the data in efficient manner.




