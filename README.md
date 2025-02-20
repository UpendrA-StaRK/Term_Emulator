# Terminal-Emulator-cpp-qt
TermE is a C++ application that utilizes Qt, a powerful GUI toolkit, to create a lightweight terminal emulator with a graphical user interface. Designed for efficient interaction with the bash shell, TermE incorporates pseudo-terminal mechanisms, enabling users to execute and control terminal commands seamlessly within a visually intuitive environment.

# Features

✅ Pseudo-Terminal Integration: Communicates with a bash shell using a master-slave pseudo-terminal mechanism.

✅ Real-time Input/Output: Supports interactive user input and live terminal output updates.

✅ Customizable Interface: Built with Qt, featuring separate areas for input and output with a responsive layout.

✅ Error Handling: Includes robust mechanisms for managing terminal communication and system call failures.

✅ Cross-Platform Compatibility: Designed to run on Linux systems with support for bash shell operations.

# Getting Started

Follow these steps to set up and build the Terminal Emulator project on your system.

# Prerequisites

Before you begin, ensure you have the following installed on your system:

  - Qt Framework: Download and install the latest version of Qt from the official Qt website. Ensure that you install both the Qt libraries and the Qt Creator IDE.The steps to setup Qt creator are mentioned ahead.
  
  - C++ Compiler: Make sure a C++ compiler compatible with Qt is installed.
  
  - Git: Install Git for cloning the repository.

# Running Terminal Emulator on your local machine

1️⃣ Setting Up Qt Creator

Run the following command to install essential packages which ensure necessary tools for C++ compilation and graphical rendering.

    sudo apt-get install build-essential libgl1-mesa-dev

  - Download and Install Qt
   
      - Visit the Qt Downloads page and select the version appropriate for your operating system.
        
      - During installation, ensure you include:
   
      - Qt libraries for your target platform.
            
      - Qt Creator IDE.
            
      - MinGW (Windows only) or GCC (Linux/macOS).

2️⃣ Cloning the Repository
Open a terminal or Git Bash and run the following command to clone the repository:

    git clone https://github.com/KeerthiSaiPG/Terminal-Emulator-cpp-qt.git

3️⃣ Building the project using Qt Creator

- Navigate to the project directory and open it using Qt Creator IDE. 

- Build the project:

     - Click on the Build button (hammer icon) to compile the project.
   
- Run the application:
  
     - Click the Run button (green play icon) to launch the Terminal Emulator.
