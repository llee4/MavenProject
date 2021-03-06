# How to Create your Maven Package

1. Open the code editor of your choice and create a new Maven project using the default archetype (usually maven-archetype-quickstart).
2. Make sure to create it in a new empty folder, and change the organization, as this will be the one under which all the files will be packaged.
3. Change the artifactID, it is the name of your project
4. Now, look at the fields created by the Maven project. The pom.xml is the main Maven file. It tells Maven what exactly your project is and what else is required to build it.
5. Create a new class inside the src/main/java folder. This is where your code for the package will go. The test folder is used for writing test code such as unit tests.
6. In the pom.xml file, make sure to change the number after maven.compiler.source to your current Java version.
7. Also notice the dependencies section in the pol.xml. This is where you can add dependent packages your project uses, like JUnit or Twitter4J.
8. To compile your project, open the Maven tab on the rigth side of the IDE. Inside, click the "package" button to create a JAR file.

This is an excellent video that summarizes this process: [https://www.youtube.com/watch?v=bxP9IuJbcDQ&t=970s](https://www.youtube.com/watch?v=bxP9IuJbcDQ&t=970s)
