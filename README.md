# Visual Studio Code Installation Guide for Python

## Install VS Code via package manager

- Windows 10/11:
  ```bash
  Set-ExecutionPolicy Unrestricted -Scope LocalMachine
  choco install vscode
  choco install git
  ```
- MacOS:
  ```bash
  brew install --cask visual-studio-code
  brew install git
  ```
## Install The following extensions:
Create a new Profile in VS Code> Call it i.e. Python
Install the following Extension:
- `Python` by `Microsoft`
- `Jupyter` by `Microsoft`

## Install Python
Follow Python installation Guide at: [https://github.com/AAU-Python-Guides/install_python_guide](https://github.com/AAU-Python-Guides/install_python_guide) 

## Working in a Visual Studio Code Environment

1. Open a workfolder
   File > Open Folder > `Select Folder to open`.
3. create or open a python file i.e. `hello.py`
5. If you did this correctly, your vs code should look like this.
   - Focus on the red squares!

![Setup1](images/vs_setup1.png)

### Select Interpreter (Python installation to use!)

1. Press `Select Interpreter`

2. Select `3.14.x` (Your installed python)
   
   Your python might be 3.14.2 or similar
   
    ![Select env3](vs_setup4.png)

3. Install needed packages using pip
   - pip install -r requirements.txt

## Running Python

VS code should look something like this
 - The `.venv` is a Python Environment, so you can have multiple setups. This is something that is the "good programming" thing to do, and I encurage you to use it. But for simplicity we are simply using the global python environment in this course!

![running1](vs_setup5.png)
