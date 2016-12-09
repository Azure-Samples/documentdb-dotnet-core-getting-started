---
services: documentdb
platforms: dotnet
author: arramac
---

# Developing a .NET Core console app using DocumentDB
This sample shows you how to use the Microsoft Azure DocumentDB service to store and access data from a .NET Core console application.

For a complete end-to-end walkthrough of creating this application, please refer to the [full tutorial on the Azure documentation page](https://azure.microsoft.com/documentation/articles/documentdb-dotnetcore-get-started/).

## Running this sample

1. Before you can run this sample, you must have the following prerequisites:
* An active Azure account. If you don't have one, you can sign up for a [free account](https://azure.microsoft.com/free/). 
    * Alternatively, you can use the [Azure DocumentDB Emulator](https://azure.microsoft.com/documentation/articles/documentdb-nosql-local-emulator) for this tutorial.
* [Visual Studio 2015 Update 3](https://go.microsoft.com/fwlink/?LinkId=691129) and [.NET Core 1.0.1 - VS 2015 Tooling Preview 2](https://go.microsoft.com/fwlink/?LinkID=827546)
    * If you're working on MacOS or Linux, you can develop .NET Core apps from the command-line by installing the [.NET Core SDK](https://www.microsoft.com/net/core#macos) for the plaform of your choice. 
    * If you're working on Windows, you can develop .NET Core apps from the command-line by installing the [.NET Core SDK](https://www.microsoft.com/net/core#windows). 
    * You can use your own editor, or download [Visual Studio Code](https://code.visualstudio.com/) which is free and works on Windows, Linux, and MacOS. 

2. Clone this repository using Git for Windows (http://www.git-scm.com/), or download the zip file.

3. If using the DocumentDB Emulator, please follow instructions at [Azure DocumentDB Emulator](https://azure.microsoft.com/documentation/articles/documentdb-nosql-local-emulator) to install and start the emulator.

If using your Azure DocumentDB account, please substitute the endpoint and authorization key in Program.cs with your account's details.

4. From a command prompt or shell, run `dotnet restore` followed by `dotnet run` to run the sample.

## About the code
The code included in this sample is intended to get you quickly started with a .NET Core console application that connects to Azure DocumentDB.

## More information

- [Azure DocumentDB Documentation](https://azure.microsoft.com/documentation/services/documentdb/)
- [Azure DocumentDB .NET SDK](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB/)
- [Azure DocumentDB .NET SDK Reference Documentation](https://msdn.microsoft.com/library/azure/dn948556.aspx)
