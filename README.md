# Disk Usage Tool

A command-line tool to display disk usage and memory consumption of the top processes on the system in a graphical and user-friendly way.

## Requirements:
- `gcc` or any other C compiler.
- A Unix-based system (such as Ubuntu, Debian).

## Installation:

1. **Build the tool using Make**:  
   After downloading the tool, open a terminal in the directory containing the tool files and run:

   ```bash
   make
   ```

   This will generate the `disku` executable.

2. **Install the tool on your system**:  
   To install the tool, run:

   ```bash
   sudo make install
   ```

3. **Usage**:  
   You can use the tool as follows:

   - To display disk usage:
     ```bash
     ./disku
     ```

   - To display the top memory-consuming processes:
     ```bash
     ./disku --memory
     ```

## Contribution:
If you would like to contribute to the development of this tool, you can open a `Pull Request` or submit suggestions on GitHub.
