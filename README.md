# GmE 205: Laboratory Exercise 1
Computational Thinking Foundations: Python, VS Code, and GitHub
# How to set up the virtual environment
The steps to set up a virtual environment:
1. Open Visual Studio Code.
2. Under the VS Code Terminal tab, select "New Terminal".
3. In the Terminal, run:
`py -m venv .venv`
`.\.venv\Scripts\activate`
4. When successful, your terminal prompt should show `(.venv)`.
# How to run Python scripts
To run a Python script:
1. Create a Python file named `hello.py` inside the `src` folder.
2. Add the following code:
`import sys`
`print("Hello GmE 205")`
`print("Python version:", sys.version)`
3. Open the VS Code Terminal and make sure the virtual environment is active.
4. Run the script using:
`python src/hello.py`
