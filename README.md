🛡 Cyber Attack Detection Dashboard

Cybersecurity attack classification project implemented using a Streamlit interface.

The system uses a trained machine learning model to classify network traffic into:

• DDoS • Malware • Intrusion

📌 Requirements

Python 3.10+

If no python is installed in your device, to install it type on your terminal :

Windows : winget install Python.Python.3.10

Linux : sudo apt update && sudo apt install python3.10

To check your python version:

python --version

⚙ Setup of the Web application

1. Clone the repository:

   git clone https://github.com/Horrynobel/Cyber_security_attack_type_detection.git

   Or download the ZIP file


With a terminal navigate into the Web_application folder

Create a virtual environment (optional but recommended):

python -m venv venv

Activate the virtual environment:

Windows: venv\Scripts\activate

Mac/Linux: source venv/bin/activate

Install required dependencies:

pip install -r requirements.txt If an error occurred, you may need to type this instead : python -m pip install -r requirements.txt

Run the web application:

streamlit run Website.py

If an error occurred, you may need to type this instead :

python -m streamlit run Website.py

Import the cybersecurity_attacks_cleaned present in the Cyber Security Attack Type Detection folder

📂 Project Structure

.devcontainer

Website.py (Streamlit interface)

attack_model.pkl

label_encoder.pkl

model_columns.pkl

model_metrics.pkl

requirements.txt

📊 Features

CSV dataset upload via sidebar

Dataset preview

Automatic feature alignment with the trained model

Model evaluation metrics (Accuracy, Precision, Recall, F1-score)

Detailed classification report per attack type

Threat distribution visualization (pie chart)

Real-time attack prediction (DDoS, Malware/SQL Injection, Intrusion, Normal)
