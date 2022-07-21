# Prime Number Checker Application

### Assignment Description
This assignment has 2 parts.  
1) Write a client/server application with two parts, a server and a client. Have the client send the server a request to compute whether a number that the user provided is prime. The server responds with yes or no, then the client displays the answer.

2) Simulate deploying the above application to a user's computer. If you're really ambitious and want to show off, after you get the simple one working, add client/server functionality to your Word Occurrences application.

Use the export feature in Eclipse to generate a runnable Jar file
In a command window, run the jar file using the syntax "java -jar <name>.jar"

### Requirements
- JavaFX runtime (https://openjfx.io/) <br>
- [PrimeCheckerApp.jar](PrimeCheckerApp.jar)

### Local Run Instructions (Windows)
1. Open Windows Command Prompt terminal
2. Navigate to the directory location of `PrimeCheckerApp.jar`
3. Enter the following into terminal:
```
java --module-path "<PATH_TO_FX/lib>" --add-modules=javafx.controls -jar PrimeCheckerApp.jar
```

### Preview
![app-demo.gif](/app-demo.gif)
