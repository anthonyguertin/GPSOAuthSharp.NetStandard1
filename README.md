# GPSOAuthSharp.NetStandard1

A .NET client library for Google Play Services OAuth written in C#.

This is a C# port of https://github.com/simon-weber/gpsoauth

# Installation

## Supported Platforms

* .NET Standard 1.1 ([Specific platforms](https://github.com/dotnet/corefx/blob/master/Documentation/architecture/net-platform-standard.md#mapping-the-net-platform-standard-to-platforms))

## Installation

Installation is done via NuGet:

    PM> Install-Package GPSOAuthSharp.NetStandard1
    
https://www.nuget.org/packages/GPSOAuthSharp.NetStandard1/

# Usage
Construct a `GPSOAuthSharp.GPSOAuthClient(email, password)`.

Use `PerformMasterLogin()` or `PerformOAuth()` to retrieve a `Dictionary<string, string>` of response values. 
