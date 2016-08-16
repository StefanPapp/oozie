#Quickstart - Oozie - Hello World

##Input Java (src)
	src/manifest.mf
	src/HelloWorld.java

	## steps to compile
		> javac Helloworld.java
		> jar cvfm HelloWorld.jar ./META-INF/MANIFEST.MF *.class
		> java -jar Helloworld.jar

##Input Oozie
	Create file: workflow.xml (via touch)
	Create file: job.properties
	Create dir lib

Copy to HDFS

oozie job -oozie <http://localhost:11000/oozie> -config job.properties -run

<http://192.168.100.21:11000/oozie>

HelloWorld-Code
 

##Components

##Job.properties
Role: Plain Map <str, str> to store configuration
See sample-file

#workflow.xml
Steering of workflow
 
 

 

 

 

 


 



 

HelloWord - Workflow.xml


 



 

security


 

If working as root, change core-xml the proxy users for oozie

 

 

#Observation


 

Move Action does not take wildcards

 



 

 

 

 



 

 

 
