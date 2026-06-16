# Blazor DataGrid — Globalization Demo

A minimal Blazor Server demo that shows how to load and apply [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) localization (culture) files from the server. The sample wires a small localization provider so  components render strings in the selected culture.

## Overview

This repository contains a compact Blazor Server sample that demonstrates how to localize  Blazor DataGrid strings by loading culture-specific resource files from the server and providing them via a custom implementation.

## Features

- Server-side Blazor demo using  DataGrid
- Includes example resource files for several cultures (for example: de-DE, fr, zh)
- Simple configuration example showing how to set the default request culture


## Prerequisites

- [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/Blazor-DataGrid-Globalization-culture-CDN.git
cd Blazor-DataGrid-Globalization-culture-CDN
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## Resources

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/global-local

**Demo**: https://blazor.syncfusion.com/demos/datagrid/default-functionalities?theme=fluent2