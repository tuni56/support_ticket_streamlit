Support Ticket Web App
A simple, interactive support ticket management system built with Streamlit, designed to streamline the process of tracking and resolving support requests.

Features
Create, update, and manage support tickets
Intuitive, user-friendly interface
Real-time data handling with Pandas
🛠️ Prerequisites
Python 3.8+ installed
Virtualenv for environment management
VSCode for editing and running the project
🚀 Getting Started
Step 1: Clone the Repository
bash
Copiar código
git clone https://github.com/yourusername/support-ticket-app.git  
cd support-ticket-app  
Step 2: Set Up a Virtual Environment
Create a virtual environment:

bash
Copiar código
python -m venv venv  
Activate the virtual environment:

On Windows:
bash
Copiar código
.\venv\Scripts\activate  
On macOS/Linux:
bash
Copiar código
source venv/bin/activate  
Install dependencies:

bash
Copiar código
pip install -r requirements.txt  
Step 3: Configure Virtual Environment in VSCode
Open the project folder in VSCode.

bash
Copiar código
code .  
Install the Python extension for VSCode (if not already installed).

Select the virtual environment as the interpreter:

Press Ctrl+Shift+P (or Cmd+Shift+P on macOS) to open the Command Palette.
Search for and select Python: Select Interpreter.
Choose the virtual environment located in the venv folder.

##💻 Run the Application
Activate the virtual environment if it’s not already active:

bash
Copiar código
.\venv\Scripts\activate   # Windows  
source venv/bin/activate  # macOS/Linux  
Run the Streamlit app:

bash
Copiar código
streamlit run app.py  
Open your browser and navigate to http://localhost:8501 to access the app.

##📜 Project Structure
bash
Copiar código
support-ticket-app/  
│  
├── app.py               # Main Streamlit app  
├── requirements.txt     # Project dependencies  
├── data/                # Folder for storing ticket data  
├── venv/                # Virtual environment folder (not included in repo)  
└── README.md            # Project documentation  

##🤝 Contributing
Fork the repository
Create a new feature branch:
bash
Copiar código
git checkout -b feature-name  
Commit your changes:
bash
Copiar código
git commit -m "Add feature-name"  
Push the branch:
bash
Copiar código
git push origin feature-name  
Open a pull request
