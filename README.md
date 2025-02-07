## Java-Maven Project


This guide provides step-by-step instructions on how to set up a Java and Maven development environment on Windows, configure system paths, and build a Java application using Maven.

### Prerequisites

Ensure you have administrative access to install software and modify system environment variables.

1. Install Java (JDK)

Step 1: Download Java JDK

Visit the Oracle JDK Download Page or install OpenJDK from Adoptium.

Download the appropriate installer for your Windows version (64-bit recommended).

Step 2: Install Java

Run the downloaded installer and follow the on-screen instructions.

Note the installation path (e.g., C:\Program Files\Java\jdk-17.0.1).

Step 3: Set up the JAVA_HOME environment variable

Open Control Panel > System > Advanced system settings.

Click Environment Variables.

Under System Variables, click New.

Enter the following:

Variable name: JAVA_HOME

Variable value: C:\Program Files\Java\jdk-17.0.1 (use your actual installation path)

Click OK to save.

Step 4: Add Java to System PATH

In the Environment Variables window, locate the Path variable under System Variables.

Click Edit, then New.

Add the Java bin directory: C:\Program Files\Java\jdk-17.0.1\bin

Click OK and close all dialogs.

Step 5: Verify Installation

Open Command Prompt and run:

```sh
java -version
javac -version
```
You should see the installed Java version.
