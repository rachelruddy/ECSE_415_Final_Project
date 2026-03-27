# ECSE 415 Final Project

## Getting Started

### 1. Install Python
If you don't have Python installed, download and install it from [python.org](https://www.python.org/downloads/).

> **Windows users:** Make sure to check **"Add Python to PATH"** during installation.

### 2. Install VS Code
Download and install [Visual Studio Code](https://code.visualstudio.com/). Once installed, open the Extensions panel (`Ctrl+Shift+X` on Windows, `Cmd+Shift+X` on Mac) and install the **Python** extension by Microsoft.

### 3. Clone the Repository
Open a terminal (VS Code has a built-in one: go to `Terminal > New Terminal`) and run:

```bash
git clone https://github.com/rachelruddy/ECSE_415_Final_Project.git
cd ECSE_415_Final_Project
```

### 4. Set Up a Virtual Environment
In the VS Code terminal, run the following:

**Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**Mac:**
```bash
python3 -m venv venv
source venv/bin/activate
```

You should see `(venv)` appear at the start of your terminal line — this means the virtual environment is active.

### 5. Select the Interpreter in VS Code
Press `Ctrl+Shift+P` (Windows) or `Cmd+Shift+P` (Mac), type **"Python: Select Interpreter"**, and choose the option that shows `venv` in the path.

You're all set!
