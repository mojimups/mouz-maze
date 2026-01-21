# mouz-maze
A tiny cursor maze game — my very first game project, built with Java JComponent back in 2022 as a college assignment.

### Run instructions
1. Install Java 17 JDK
2. Run run.bat

### Build instructions
1. Install Java 17 JDK
2. Open cmd in this folder
3. Type in:
   & "C:\Program Files\Java\jdk-17\bin\jpackage.exe" `
   --type app-image `
   --input "Source Code\bin" `
   --main-jar "MouzMaze.jar" `
   --main-class "RunMouzMaze" `
   --dest "dist" `
   --name "MouzMaze" `
   --app-version "1.0.0" `
   --vendor "mojimups" `
   --icon "favicon.ico"
4. The finished build will be in /dist