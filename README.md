<h1>Simple JavaFX 11 and Java 11 Module</h1>

<p> The goal of this project is to understand Maven project structure in relation to Java Modularity context</p>

Prerequisite:
- JDK 11 installed
- JavaFX 11 installed

To run this project, simply follow this steps:
1) clone this project (git clone https://github.com/Senopratomo/jfxmodulardemo.git)
2) go to the resulting directory (cd jfxmodulardemo)
3) run 'mvn clean install'
4) run 'java --module-path <path to all the modular JAR and also to JavaFX JAR separated by semi-colon (;)> 
        -m gui/org.senolab.gui'
5) Enjoy!
