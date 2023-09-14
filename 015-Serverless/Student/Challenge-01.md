# Challenge 01 - Setup

**[Home](../README.md)** - [Next Challenge >](./Challenge-02.md)

## Pre-requisites

- Your laptop: Win, MacOS or Linux OR A development machine that you have **administrator rights**.
- Active Azure Subscription with **contributor level access or equivalent** to create or modify resources.

## Introduction

The first challenge is to setup an environment that will help you build the Tollbooth application and deploy it locally. We need to make sure everything is working before bringing it to Azure.

## Description

Set up your *local* environment:

- Visual Studio or Visual Studio Code
    - Azure development workload for Visual Studio 2022 or 2019
    - Azure Functions and Azure Functions Core Tools
    - [Node.js 8+](https://nodejs.org/en/download/): Install latest long-term support (LTS) runtime environment for local workstation development. A package manager is also required. Node.js installs NPM in the 8.x version. The Azure SDK generally requires a minimum version of Node.js of 8.x. Azure hosting services, such as Azure App service, provides runtimes with more recent versions of Node.js. If you target a minimum of 8.x for local and remove development, your code should run successfully.
    - .NET 6 SDK
    - [VS Code Todo Tree Extension](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
    - Any extentions required by your language of choice

*To setup Azure Functions on Visual Studio Code, [follow this guide.](https://docs.microsoft.com/en-us/azure/azure-functions/functions-develop-vs-code)*
 
The zip file, `Resources.zip`, contains the source code and supporting files for this hack and is available in the Teams share channel (see "Files" tab at the top of the top-level group).  Uncompress the file on your local workstation. The file is available for download [here](https://github.com/3clouder/ServerlessSeptember/blob/master/015-Serverless/Student/Resources.zip).

## Success Criteria

1. Confirm that Visual Studio (2019 or 2022) or VS Code is installed and is capable of running .NET 6 or higher. **HINTS**: The Help > About screen will aid in demonstrating a successful Visual Studio installation. Use the "node -v" and "dotnet --version" commands in the Terminal > New Terminal panel for your Node.js and .NET versions, respectively.
1. Confirm that you have the following folders locally wherever you unpacked the `Resources.zip` file:
    - `/Tollbooth`
    - `/license plates`

*Provide a screenshot from Visual Studio or VS Code to the Proctor group as your proof artifact.*