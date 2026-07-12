# .NET MAUI 101

Welcome to the .NET MAUI 101 training!

This repository contains the starter template used throughout the workshop. During the training, you'll build on this project as you work through the exercises.

> **Note**
> The training materials are provided separately. This repository contains only the project template you'll use during the session. See the training materials for a complete list of project requirements and guidance on getting started.

---

## Prerequisites

Before starting, make sure you have:

- .NET 10 SDK (or the version specified by your instructor)
- Visual Studio Code
- C# Dev Kit extension
- .NET MAUI workload installed
- .NET MAUI Extension
Verify your installation:

```bash
dotnet --version
dotnet workload list
```

If the MAUI workload is missing:

```bash
dotnet workload install maui
```

---

## Clone the Repository

Clone this template into your own repository (or clone the repository provided by your instructor):

```bash
git clone <your-repository-url>
cd <repository-name>
```

Restore dependencies:

```bash
dotnet restore
```

---

## Running the Application

Open the project in Visual Studio Code.

### Select a Target

Depending on your development environment, you can run on:

- Android Emulator
- iOS Simulator (macOS only or connected device)
- Windows
- Mac Catalyst (macOS only or connected device)

### Run from the Terminal

For Windows:

```bash
dotnet build -t:Run -f net10.0-windows10.0.19041.0
```

For Android:

```bash
dotnet build -t:Run -f net10.0-android
```

For iOS (macOS):

```bash
dotnet build -t:Run -f net10.0-ios
```

For Mac Catalyst (macOS):

```bash
dotnet build -t:Run -f net10.0-maccatalyst
```

> **Tip**
> Ensure your emulator or simulator is running before launching the application.

---

## Helpful Commands

Restore packages:

```bash
dotnet restore
```

Build the project:

```bash
dotnet build
```

Clean the project:

```bash
dotnet clean
```

List installed workloads:

```bash
dotnet workload list
```

Update workloads:

```bash
dotnet workload update
```

---

## Learning Resources

If you'd like to learn more about .NET MAUI, these resources are a great place to start:

- .NET MAUI Documentation  
  https://learn.microsoft.com/dotnet/maui/

- .NET MAUI Fundamentals  
  https://learn.microsoft.com/dotnet/maui/fundamentals/

- Build your first .NET MAUI app  
  https://learn.microsoft.com/dotnet/maui/get-started/first-app

- .NET MAUI Samples  
  https://github.com/dotnet/maui-samples

---

## Workshop Notes

Throughout the training you'll:

- Explore the project structure
- Build UI with XAML
- Work with data binding and MVVM
- Worth with the MAUI Community Toolkit
- Add navigation between pages
- Implement common .NET MAUI features

The template is intentionally minimal so you can focus on the concepts covered during the training.

---

## Questions?

If you run into setup issues before or during the workshop, contact your instructor or training organizer.