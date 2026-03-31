# This is a JAVA Note

**JDK - JAVA DEVELOPMENT KIT**
**IDE - INTEGRATED DEVELOPMENT ENVIRONMENT**

**☕ Java Fundamentals — Notes**

Java code is written in .java files (e.g. Hello.java)
The main method is the entry point of a Java program
args parameter holds any program arguments passed at startup

**⚙️ Two-Step Process to Run Java Code**
_Step 1 — Compile_

The Java Compiler (javac) converts .java source code into Java Byte Code stored in .class files
Example: Hello.java → Hello.class

_Step 2 — Run_

The Java Virtual Machine (JVM) reads and executes the .class byte code
Byte code is system independent — runs on Mac, Windows, different processor architectures

**📦 Java Standard Edition (Java SE) APIs**

Pre-built classes like System that your code relies on
Foundational APIs for networking, file access, collections, and more
Included in the JDK

**🛠️ JDK — Java Development Kit**

_Combination of:_

- JVM — runs byte code
- Java SE APIs — standard libraries
- Tools — java (runtime) and javac (compiler)

_You cannot develop Java apps without the JDK_

**🏢 Java EE vs Jakarta EE**

- Java EE — Enterprise Edition APIs for web apps, databases, enterprise integrations
- Java EE is NOT part of the JDK
- Oracle stopped developing Java EE and donated it to the Eclipse Foundation
- Now rebranded as Jakarta EE
- ⚠️ This course focuses on Java SE only

Installation of the jdk

go to this website:

https://www.oracle.com/java/technologies/downloads/

once you downloaded it:

1. go to Environment variables and click the button
2. go for the system variables
3. add JAVA_HOME and add the path where you installed the jdk, if existing just change the path
4. find the path on system variables, select and edit it. You can click the new or edit: add the path what you did on JAVA_HOME and add \bin
5. To check if it was working. Go to cmd and prompt **java -version**
