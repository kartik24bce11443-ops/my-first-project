Campus Course & Records Manager (CCRM) (Java Project)
Project Full description - 

The Campus Course & Records Manager (CCRM) is a console-based Java SE application designed to manage students, courses, enrollments, grades, and file operations for an educational institute. It demonstrates core Java concepts, OOP principles, modern Java APIs (NIO.2, Streams, Date/Time), design patterns (Singleton, Builder), and robust exception handling. The application features a menu-driven CLI for managing students, courses, enrollments, grades, and file utilities (import/export CSV, backups).
How to Run

Requirements: Java Development Kit (JDK) 17 or later, Eclipse IDE (or any Java IDE).
Clone the Repository:git clone <repository-link>


Navigate to Project Directory:cd ccrm


Compile and Run:
Using Eclipse: Import the project, set up the run configuration, and run edu.ccrm.cli.CCRMMain.
Using terminal:javac -d bin src/edu/ccrm/*/*.java
java -cp bin edu.ccrm.cli.CCRMMain




Enable Assertions (optional, for invariant checks):java -ea -cp bin edu.ccrm.cli.CCRMMain


Sample Data: Use provided CSVs in the test-data folder for importing students and courses.

Evolution of Java

1995: Java 1.0 released by Sun Microsystems, introducing "Write Once, Run Anywhere."
1998: Java 2 (J2SE 1.2) added Swing, Collections Framework.
2004: Java 5 introduced generics, enums, annotations, enhanced for loop.
2011: Java 7 brought try-with-resources, NIO.2, switch-on-strings.
2014: Java 8 introduced Streams API, lambdas, Date/Time API.
2017–2023: Java 9–17 added modules, records, sealed classes, pattern matching, and long-term support (LTS) releases (11, 17).
2025 (current): Java continues to evolve with Project Valhalla (value types), Loom (virtual threads), and Panama (foreign function/memory API).

Java ME vs SE vs EE



Platform
Purpose
Key Features
Use Case



Java ME
Micro Edition for resource-constrained devices
Lightweight APIs, CLDC, MIDP
Embedded systems, mobile phones (pre-Android era)


Java SE
Standard Edition for general-purpose applications
Core APIs, JVM, NIO.2, Streams, Date/Time
Desktop apps, CLI tools, backend systems


Java EE
Enterprise Edition for large-scale, distributed systems
Servlets, JSP, EJB, JPA, REST
Web apps, enterprise services, microservices


Java Architecture: JDK, JRE, JVM

JVM (Java Virtual Machine): Executes Java bytecode, provides platform independence, manages memory (GC), and enforces security.
JRE (Java Runtime Environment): Includes JVM + standard libraries for running Java applications.
JDK (Java Development Kit): Superset of JRE + development tools (javac, javadoc) for compiling and debugging.
Interaction: Developers use JDK to write and compile code into bytecode. JRE runs the bytecode on the JVM, which interprets or JIT-compiles it to native machine code.

Install & Configure Java on Windows

Download JDK:
Visit Oracle JDK or adopt OpenJDK (e.g., Adoptium).
Choose JDK 17 (LTS) for Windows.


Install JDK:
Run the installer, follow prompts, and note the installation path (e.g., C:\Program Files\Java\jdk-17).


Set Environment Variables:
Add JAVA_HOME: Set to C:\Program Files\Java\jdk-17.
Update PATH: Append %JAVA_HOME%\bin.
Verify: Run java -version in Command Prompt.
Screenshot: See screenshots/java-version.png.


Test Installation:java -version
javac -version



Using Eclipse IDE

Install Eclipse:
Download Eclipse IDE for Java Developers.
Install and launch.


Create New Project:
File → New → Java Project.
Name: CCRM.
Ensure JRE is set to JDK 17.


Import Source:
Copy src folder from repository to project’s src directory.
Refresh project in Eclipse.


Run Configuration:
Right-click CCRMMain.java → Run As → Java Application.
Screenshot: See screenshots/eclipse-setup.png and screenshots/eclipse-run.png.


Run Program:
Use the


