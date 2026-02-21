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
   pip install -r requirements.txt
   ```

### Running the Application
This project includes a Streamlit application for making real-time predictions. You can also access the [Live Demo](https://fraud-detection-v1.streamlit.app/).

1. Run the Streamlit app locally:
   ```bash
   streamlit run fraud_detection.py
   ```
2. The app will open in your default browser, allowing you to enter transaction details:
   - **Transaction Type**: PAYMENT, TRANSFER, CASH_OUT, DEPOSIT.
   - **Amount**: The transaction value.
   - **Sender/Receiver Balances**: Initial and final balances for both accounts.

3. Click the **Predict** button to see if the transaction is flagged as a "Possible Fraudulent Transaction" or "No Fraudulent Transaction".

### Usage
Ensure the virtual environment is activated before running the `analysis_model.ipynb` notebook or the Streamlit app.
If you are using an IDE like VS Code or PyCharm, select the interpreter located in `venv/bin/python` (or `venv/Scripts/python.exe` on Windows).

## Project Structure
- `AIML_Dataset.csv`: The dataset containing financial transaction records.
- `analysis_model.ipynb`: A Jupyter notebook for data analysis and model training.
- `fraud_detection.py`: The Streamlit application for fraud prediction.
- `fraud_detection_pipeline.pkl`: The saved machine learning model pipeline.
- `requirements.txt`: List of Python dependencies for the project.
- `venv/`: The virtual environment containing all dependencies.
