<h1 align="center">Support Ticket Web App</h1>
<p align="center">
  A simple, interactive support ticket management system built with <strong>Streamlit</strong>, designed to streamline the process of tracking and resolving support requests.
</p>

---

<h2>✨ Features</h2>
<ul>
  <li>Create, update, and manage support tickets</li>
  <li>Intuitive, user-friendly interface</li>
  <li>Real-time data handling with <strong>Pandas</strong></li>
</ul>

---

<h2>🛠️ Prerequisites</h2>
<ul>
  <li><strong>Python 3.8+</strong> installed</li>
  <li><strong>Virtualenv</strong> for environment management</li>
  <li><strong>VSCode</strong> for editing and running the project</li>
</ul>

---

<h2>🚀 Getting Started</h2>

<h3>Step 1: Clone the Repository</h3>
<pre>
<code>
git clone https://github.com/yourusername/support-ticket-app.git
cd support-ticket-app
</code>
</pre>

<h3>Step 2: Set Up a Virtual Environment</h3>
<ol>
  <li>Create a virtual environment:
    <pre><code>python -m venv venv</code></pre>
  </li>
  <li>Activate the virtual environment:
    <ul>
      <li>On <strong>Windows</strong>:
        <pre><code>.\venv\Scripts\activate</code></pre>
      </li>
      <li>On <strong>macOS/Linux</strong>:
        <pre><code>source venv/bin/activate</code></pre>
      </li>
    </ul>
  </li>
  <li>Install dependencies:
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
</ol>

<h3>Step 3: Configure Virtual Environment in VSCode</h3>
<ol>
  <li>Open the project folder in VSCode:
    <pre><code>code .</code></pre>
  </li>
  <li>Install the <strong>Python</strong> extension for VSCode (if not already installed).</li>
  <li>Select the virtual environment as the interpreter:
    <ul>
      <li>Press <code>Ctrl+Shift+P</code> (or <code>Cmd+Shift+P</code> on macOS) to open the Command Palette.</li>
      <li>Search for and select <strong>Python: Select Interpreter</strong>.</li>
      <li>Choose the virtual environment located in the <code>venv</code> folder.</li>
    </ul>
  </li>
</ol>

---

<h2>💻 Run the Application</h2>
<ol>
  <li>Activate the virtual environment if it’s not already active:
    <ul>
      <li>On <strong>Windows</strong>:
        <pre><code>.\venv\Scripts\activate</code></pre>
      </li>
      <li>On <strong>macOS/Linux</strong>:
        <pre><code>source venv/bin/activate</code></pre>
      </li>
    </ul>
  </li>
  <li>Run the Streamlit app:
    <pre><code>streamlit run app.py</code></pre>
  </li>
  <li>Open your browser and navigate to <code>http://localhost:8501</code> to access the app.</li>
</ol>

---

<h2>📜 Project Structure</h2>
<pre>
<code>
support-ticket-app/
│
├── app.py               # Main Streamlit app
├── requirements.txt     # Project dependencies
├── data/                # Folder for storing ticket data
├── venv/                # Virtual environment folder (not included in repo)
└── README.md            # Project documentation
</code>
</pre>

---

<h2>🤝 Contributing</h2>
<ol>
  <li>Fork the repository</li>
  <li>Create a new feature branch:
    <pre><code>git checkout -b feature-name</code></pre>
  </li>
  <li>Commit your changes:
    <pre><code>git commit -m "Add feature-name"</code></pre>
  </li>
  <li>Push the branch:
    <pre><code>git push origin feature-name</code></pre>
  </li>
  <li>Open a pull request</li>
</ol>

---

<p align="center"><strong>Happy coding! 😊</strong></p>





