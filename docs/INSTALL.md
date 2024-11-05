# Installation Instructions for XGameForge

To get started with XGameForge, follow these steps to configure your development environment for C#:

## 1. Install an Integrated Development Environment (IDE)

Choose one of the following IDEs for C# development, based on your preference and operating system:

- **Visual Studio (Windows)**
  - **Installation**: Download and install Visual Studio Community Edition from the [official website](https://visualstudio.microsoft.com/).
  - **Required Workloads**:
    - During installation, select the following workloads:
      - **.NET desktop development**: for building desktop applications.
      - **Game Development with C#**: for game development features.
    - Ensure that the necessary SDKs and components are installed.

- **JetBrains Rider (Windows and Linux)**
  - **Installation**: Download JetBrains Rider from the [official website](https://www.jetbrains.com/rider/).
  - **Licensing**: A free trial is available, but a paid license is required for continued use.
  - **Setup**: Follow the installation instructions specific to your operating system.

## 2. Install the .NET SDK

To develop C# applications, you need the .NET SDK installed on your system:

- **Windows**
  - Download and install the .NET SDK from the [.NET download page](https://dotnet.microsoft.com/download).

- **Linux**
  - Use the terminal to install the .NET SDK. The installation steps will vary based on your Linux distribution. Refer to the [.NET installation guide](https://docs.microsoft.com/en-us/dotnet/core/install/linux) for detailed instructions.

## 3. Verify the Installation

After installation, verify that the IDE and .NET SDK are properly installed:

- **For Visual Studio**
  - Open Visual Studio and create a new C# project to ensure it initializes correctly.

- **For JetBrains Rider**
  - Launch Rider and create a new C# project to confirm proper setup.

- **For .NET SDK**
  - Open a terminal and run the following command:
    ```bash
    dotnet --version
    ```
  - This command should output the installed version of the .NET SDK.

## 4. Configure Build Tools

Set up any additional build tools necessary for your development process:

- **Windows**
  - Ensure that the Visual Studio Build Tools are installed if you plan to build from the command line.

- **Linux**
  - Install Mono if required for compatibility with certain C# features. Use the following command to install Mono:
    ```bash
    sudo apt install mono-complete
    ```

## 5. Set Up Version Control

Make sure to configure Git for version control:

- Install Git on both Windows and Linux.
- Set up your global Git configuration with your user name and email:
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "youremail@example.com"
```

## Summary

By following these steps, you will have a fully configured development environment for C# on both Windows and Linux, enabling you to start developing XGameForge effectively.
