# Financial Fraud Detection Project

## Setup and Requirements
To avoid modifying the System Python, this project uses a virtual environment for all package installations.

### Prerequisites
- Python 3

### Installation
1. Create a virtual environment:
   ```bash
   python3 -m venv venv
   ```
2. Activate the virtual environment:
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     .\venv\Scripts\activate
     ```
3. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

### Usage
Ensure the virtual environment is activated before running the `analysis_model.ipynb` notebook or any other Python scripts in this project.
If you are using an IDE like VS Code or PyCharm, select the interpreter located in `venv/bin/python` (or `venv/Scripts/python.exe` on Windows).

## Project Structure
- `AIML Dataset.csv`: The dataset containing financial transaction records.
- `analysis_model.ipynb`: A Jupyter notebook for data analysis and fraud detection.
- `venv/`: The virtual environment containing all dependencies.
