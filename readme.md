1. Virtual Environment Setup

To initiate a Python virtual environment on a Mac, follow these steps: create the virtual environment.

->    python3 -m venv '<name of that virtual environment folder (venv)>'

This is needed so that you don't need to always download libraries globally and everything is isolated in this separate environment for your project so like it can eradicate issue of version conflict


Once the virtual environment is created, you need to activate it to start using it. This will modify your shell's PATH to include the virtual environment's Python and pip executables.
Code

    source '<name of that virtual environment folder (venv)>'/bin/activate

Now here you can install any python, pip libraries, dependencies, versions


When you are finished working within the virtual environment, you can deactivate it to return to your system's global Python environment:
Code

    deactivate    