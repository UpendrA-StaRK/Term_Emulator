# Term_Emulator

TermE is a C++ application that utilizes Qt, a powerful GUI toolkit, to create a lightweight terminal emulator with a graphical user interface. Designed for efficient interaction with the bash shell, TermE incorporates pseudo-terminal mechanisms, enabling users to execute and control terminal commands seamlessly within a visually intuitive environment.

## Features

✅ Pseudo-Terminal Integration: Communicates with a bash shell using a master-slave pseudo-terminal mechanism.

✅ Real-time Input/Output: Supports interactive user input and live terminal output updates.

✅ Customizable Interface: Built with Qt, featuring separate areas for input and output with a responsive layout.

✅ Error Handling: Includes robust mechanisms for managing terminal communication and system call failures.

✅ Cross-Platform Compatibility: Designed to run on Linux systems with support for bash shell operations.

## Getting Started

Follow these steps to set up and build the Terminal Emulator project on your system.

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- **Qt Framework**: Download and install the latest version of Qt from the official Qt website. Ensure that you install both the Qt libraries and the Qt Creator IDE. The steps to set up Qt Creator are mentioned ahead.

- **C++ Compiler**: Make sure a C++ compiler compatible with Qt is installed.

- **Git**: Install Git for cloning the repository.

### Running Terminal Emulator on Your Local Machine

#### 1️⃣ Setting Up Qt Creator

Run the following command to install essential packages which ensure necessary tools for C++ compilation and graphical rendering:

```sh
sudo apt-get install build-essential libgl1-mesa-dev
```

- **Download and Install Qt**
  - Visit the Qt Downloads page and select the version appropriate for your operating system.
  - During installation, ensure you include:
    - Qt libraries for your target platform.
    - Qt Creator IDE.
    - MinGW (Windows only) or GCC (Linux/macOS).

#### 2️⃣ Cloning the Repository

Open a terminal or Git Bash and run the following command to clone the repository:

```sh
git clone https://github.com/UpendrA-StaRK/Term_Emulator.git
```

#### 3️⃣ Building the Project Using Qt Creator

- Navigate to the project directory and open it using Qt Creator IDE.
- **Build the project:**
  - Click on the **Build** button (hammer icon) to compile the project.
- **Run the application:**
  - Click the **Run** button (green play icon) to launch the Terminal Emulator.

---

## Installation & Usage

### Prerequisites

- Qt Framework
- C++ Compiler

### Build Instructions

1. Open the project in Qt Creator or run:
   ```sh
   qmake CppTdoc.pro
   make
   ```
2. Run the application:
   ```sh
   ./TerminalEmulatorApp
   ```

## Contribution

Feel free to contribute by submitting issues and pull requests.

## License

[Specify License Here]

