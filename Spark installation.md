Installing spark python API(pyspark) on Windows

prerequisite:
	1. python 2.7+ or 3.4+
	2. JDK 8+
	
Follow below steps if listed prerequisite not in place.

1. Installing Python
	
	a. Get Python from https://www.python.org/downloads/
	b. set system PATH
		e.g 
		C:\Users\<user_name>\AppData\Local\Programs\Python\Python37\
	c. check with below command in command prompt
		python --version


2. Installing JDK
	a. Install JDK 8+
	   JDK 8 download https://www.oracle.com/technetwork/java/javaee/downloads/jdk8-downloads-2133151.html
	b. set system PATH or JAVA_HOME environment variable pointing to a Java installation.
		e.g C:\Program Files\Java\jdk1.8.0_181\bin;
	c. check with below command in command prompt
		java -version

3. Installing pyspark (python API)
	pip install pyspark


And it is done. To interactively work in spark type pyspark in command prompt.
