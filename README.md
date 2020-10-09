# PRODLOG-Proof-Checker
Interactive proof checker for creating Fitch-style proofs in propositional and predicate logic. See README.pdf for more detailed instructions.

The following JAR files can be found and downloaded from lib. These need to be added to the program's module path:

•	javafx-swt.jar
•	javafx.base.jar
•	javafx.controls.jar
•	javafx.fxml.jar
•	javafx.graphics.jar
•	javafx.media.jar
•	javafx.swing.jar
•	javafx.web.jar

The JDK 11 library was used as the specific JRE for this project  - it is strongly recommended that the code be run with JDK11.

The following VM arguments need to be added to the run configurations:

•	--module-path (location of JavaFX JAR files in memory) 
•	--add-modules=javafx.base 
•	--add-modules=javafx.controls 
•	--add-modules=javafx.fxml 
•	--add-modules=javafx.graphics 
•	--add-modules=javafx.media 
•	--add-modules=javafx.swing 
•	--add-modules=javafx.web

The entry point to the programme is through running GUIView.java. 

To run the JUnit test classes, the JUnit 5 library should be configured in the class path. 

Furthermore, to ensure correct outputs, run with a UTF-8 character set.

If in doubt, open and run the code in Eclipse.
