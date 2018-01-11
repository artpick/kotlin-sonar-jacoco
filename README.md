# Kotlin hello-world example with Maven, SonarQube and Jacoco

## Prerequisites to running the example

 * download Maven directly from the [Apache Maven homepage](http://maven.apache.org/download.html)
 * install and configure your system as described in [the installation section](http://maven.apache.org/download.html#Installation)
 * download and install SonarQube [SonarQube](https://www.sonarqube.org/) 
 * download and install the SonarQube plugin [sonar-kotlin](https://github.com/arturbosch/sonar-kotlin)
 
 * make sure your SonarQube is up and running [http://localhost:9000](http://localhost:9000)
   * how to make it running [huhu](https://docs.sonarqube.org/display/SONAR/Get+Started+in+Two+Minutes) 
 
## Compile/Test/Run/SonarQube/Jacoco the example

If you have maven on your path, simply execute:

	mvn clean install sonar:sonar
	
Check you got the coverage. 

## Warnings!

 * ~~Keep the maven java structured project **src/main/java**~~ (this note seems to be wrong since I tested it with another project, I feel like the next note was the real issue)
 * You can't just write code in the root folder, it will not be analysed
 
