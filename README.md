# makefile



'Make' is a linux utility requires a file with name 'Makefile' (or makefile ), which holds set of tasks to be executed. You may have used make to compile a program from source code. Most open source projects use make to compile a final executable binary, which can then be installed using make install.

The makefile contains a list of rules. These rules tell the system what commands you want to be executed.

Use below command to install:

	sudo apt-get install make
 
Example:
	Here we are compiling a java program & generating a jar file then executing the jar file by passing arguments.




```
  all:
	 javac program/*.java
	 jar -cmf manifest.mf jarFileName.jar program
	 @echo "+ to run type: java -jar jarFileName.jar"
	 @echo "+ to run with command line arguments, simply append them to the line above" 
```

 
