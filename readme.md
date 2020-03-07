ADS_Assignment- Rabin-Karp Algorithm for String matching
Principle: 
1. This method is based on mathematical formulation used to convert pattern and substring into numerical value.
2. Instead of comparing individual character of string and pattern numerical value of pattern and string is compared.

What does this .java files contains ? 
ADS_ASSIGNMENTFINAL.java contains the main method.
prime.java contains prime class in which a methods generate_prime is defined for generation of prime number.
print_index.java contains print_index class in which print method is defined.
ssum.java contains ssum class under which sum and sub_sum methods are defined.
search.java contains search class in which search_pattern method is defined to find that the string contains pattern or not.

How to run .jar file ?
When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "ADS_ASSIGNMENTFINAL.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.

Sample Output: 


<img src="https://i.ibb.co/xXJkv83/snip7.jpg" height="700" width="500" />
