# developer-interview-java

This provides a simple Spring Boot application to be used as part of the interview process for Java developers at Companies House. It is intended to be used as a starting point for candidates to build upon and demonstrate their skills in Java and Spring Boot.

## Pre-requisites

* Java 21 (if running locally)
* IDE of choice (e.g. IntelliJ, Eclipse, VS Code)
* Maven (optional, if not using the wrapper)
* Docker (optional, if running in a container)
* [sdkman](https://sdkman.io/) (optional)

## Running the application

The application can be run using the following command:

```bash
./mvnw spring-boot:run
```

## Calling the application

The application is running on port 8080 by default.

## At the end of the test

### On Unix-based terminals

If you're running within a Unix-based terminal, you can run the following command to create a zip file of your work:

```bash
./bin/zip-my-code
```

This will create a zip file in the root of the project with your code, which you can then share with us.

### Windows PowerShell

If you're operating on Windows, you can create a zip file of your work using the following command in PowerShell:

```powershell
Compress-Archive -Path .\* -DestinationPath techtest-<your-name>.zip
```

Where `<your-name>` should be replaced with your actual name. This command will create a zip file in the root of the project with your code, which you can then share with us.

### Windows File Explorer

If you're using Windows File Explorer, you can create a zip file of your work by following these steps:

1. Navigate to the root directory of the project.
2. Select all the files and folders in the project (you can use Ctrl + A).
3. Right-click on the selected files and choose "Send to" > "Compressed (zipped) folder".
4. Name the zip file as `techtest-<your-name>.zip`, replacing `<your-name>` with your actual name.
5. The zip file will be created in the root of the project, which you can then share with us.
