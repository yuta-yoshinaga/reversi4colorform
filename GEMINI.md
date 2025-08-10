# GEMINI.md
This file provides guidance to GEMINI when working with code in this repository.

## High-level Code Architecture
This repository contains a C# Windows Forms application named `Reversi4colorForm`. The core logic for the Reversi game and its UI components are located within the `Reversi4colorForm/` directory. The `docs/` directory contains Doxygen-generated API documentation for the project.

## Common Commands

### Build
To build the solution, navigate to the root directory of the repository and use `dotnet build`:
```bash
dotnet build Reversi4colorForm.sln
```

### Run
After building, you can run the application from the build output directory. Assuming a successful build, the executable will be in `Reversi4colorForm/bin/Debug/netX.X/Reversi4colorForm.exe` (replace `netX.X` with the target framework version, e.g., `net6.0`):
```bash
dotnet run --project Reversi4colorForm/Reversi4colorForm.csproj
```

