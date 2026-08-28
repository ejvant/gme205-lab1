# GmE 205: Laboratory Exercise 1
**Computational Thinking Foundations: Python, VS Code, and GitHub**
## How to set up the virtual environment
The steps to set up a virtual environment:
1. Open Visual Studio Code.
2. Under the VS Code Terminal tab, select "New Terminal".
3. In the Terminal, run:

   `py -m venv .venv`

   `.\.venv\Scripts\activate`

4. When successful, your terminal prompt should show `(.venv)`.
## How to run Python scripts
To run a Python script:
1. Create a Python file named `hello.py` inside the `src` folder.
2. Add the following code:

   `import sys`

   `print("Hello GmE 205")`

   `print("Python version:", sys.version)`

3. Open the VS Code Terminal and make sure the virtual environment is active.
4. Run the script using:
   `python src/hello.py`
## Run Instructions
To run the Python script, open the VS Code Terminal and run:

   `python src/hello.py`

## Reflection: Computational Thinking Lenses
Before working with the dataset, I focused on the key characteristics of the dataset, such as its structure, coordinate values, data validity, and spatial extent to determine whether the dataset was suitable for further use. These checks helped me to understand the structure and characteristics of the data and identify errors and its limitations before it is used for further analysis. The CSV is treated as a consistent dataset where id, longitude, and latitude represent the geographic position of each point through coordinates recorded in WGS84 decimal degrees. Another assumption is that the coordinate values were correctly recorded and corresponded to locations within or around UP Diliman. The script can automatically perform basic and routine checks on data structure, missing values, coordinate ranges, and spatial extent. On the other hand, a human should check whether the coordinates are accurate, within the scope of expected study area, and relevant to the intended analysis. If the dataset becomes very large, processing may take more time and require greater memory. This may result in loading the script slowly and making visualization more difficult to interpret.

Edited on GitHub web interface and VS Code
