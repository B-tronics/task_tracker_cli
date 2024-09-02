# Task Tracker CLI

This simple console line application lets you manage your tasks.

## Prerequisites

Before you begin, ensure you have the following software installed on your system:

1. **Java Development Kit (JDK) 22**
   - Download and install JDK 22 from [Oracle](https://www.oracle.com/java/technologies/javase-jdk22-downloads.html) or [Adoptium](https://adoptium.net/).
   - Set the `JAVA_HOME` environment variable to the JDK 22 installation path.
   - Add the JDK `bin` directory to your system's `PATH`.

2. **Apache Maven 3.9.0 or Higher**
   - Download and install Maven from the [Apache Maven website](https://maven.apache.org/download.cgi).
   - Set the `MAVEN_HOME` environment variable to the Maven installation path.
   - Add the Maven `bin` directory to your system's `PATH`.

### Installation

- git clone https://github.com/btronics/task_tracker_cli.git
- cd repository
- mvn clean package

### Usage

To run the CLI program, use the following command:

`java -jar target/tasktrackercli-1.0-SNAPSHOT.jar [options] [arguments]`

### Examples

To display all options run the program without any argument

`java -jar target/tasktrackercli-1.0-SNAPSHOT.jar` 


