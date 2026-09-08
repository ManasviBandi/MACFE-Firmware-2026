# MACFE Firmware 2026

A small C++ project created for my application to the **McMaster Formula Electric Software Subteam**.

The project contains a simple C++ program and a GitHub Actions workflow that automatically builds and runs the program when changes are pushed or a pull request is opened.

## Project Structure

```text
MACFE-Firmware-2026/
├── hello.cpp
├── README.md
└── .github/
    └── workflows/
        └── build.yml
```

## Requirements

* C++ compiler
* C++11 or newer
* GitHub account for viewing the CI workflow

## Running Locally

### 1. Clone the repository

```bash
git clone https://github.com/ManasviBandi/MACFE-Firmware-2026.git
cd MACFE-Firmware-2026
```

### 2. Compile the program

```bash
g++ -std=c++11 hello.cpp -o hello
```

### 3. Run the program

```bash
./hello
```

Expected output:

```text
Hello World
```

## Continuous Integration

This repository uses **GitHub Actions** to automatically validate changes.

The workflow:

1. Checks out the repository
2. Compiles the C++ program using C++11
3. Runs the resulting executable
4. Runs automatically on pushes to `main` and pull requests targeting `main`

This provides a basic example of how automated checks can be integrated into a software development workflow.

## Purpose

This project was created as part of my application to the **MAC Formula Electric Software Subteam**, with particular interest in the **DevOps** area.

I'm interested in learning more about CI/CD, Linux, automation, infrastructure, and the tooling that helps software teams build and test code reliably.

## Author

**Manasvi Bandi**

GitHub: https://github.com/ManasviBandi
