# Overview

If you're not looking to build the application and simply want to download it and start using it.  All you really need for setup is
the .NET Core pre-requisites.

## Pre-requisites

### .NET Core:
- Download and install the .NET Core 3.1 here (https://dotnet.microsoft.com/download/dotnet-core/3.1)

## Get Application Inspector
- Download Application Inspector by selecting the pre-built package for the operating system of choice shown under the Assets section
of the [Releases](https://github.com/microsoft/ApplicationInspector/releases) page and expand the files to your local system drive
using the decompression utility of choice e.g. WinZip, 7zip, Gzip etc. Or if you have dotnet already installed, use the dotnet command `dotnet tool install --global Microsoft.CST.ApplicationInspector.CLI` more fully described here on our wiki https://github.com/microsoft/ApplicationInspector/wiki/7.-NuGet-Support

## Start Using It

That's it.  Start using the application by selecting and downloading the source code you want to scan to a local directory then run Application Inspector against it either from the source code directory or the Application Inspector install directory using the instructions found on this site on the home page or Readme.md file.  

## Getting Help

You can also get help directly from the application by simply typing in the application name without a command
or with a command to get the required and optional arguments for a given command.

Windows: just run the .exe i.e. applicationinspector.exe
Other: run as dotnet applicationinspector.dll

* applicationinspector <no arguments> - to get a list of available top level commands
* applicationinspector [command] < no arguments> - to get a list of required and optional arguments to supply with the selected command
* applicationinspector [command] [arguments] -to run a given command with the required or optional parameters
