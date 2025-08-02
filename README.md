# 🤖 AI Chatbot using OpenAI & Flask

An intelligent and conversational AI chatbot built using **Python**, **Flask**, and the **OpenAI GPT API**. This project serves as a simple but powerful example of integrating generative AI models into a web application.

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the App](#running-the-app)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📖 About the Project

This is a web-based chatbot that leverages the power of **OpenAI's GPT model** to respond to user queries in natural language. It provides a clean frontend for chatting and a Flask backend to handle requests and interact with the OpenAI API.

Whether you're learning Flask or exploring AI capabilities, this project is a solid starting point for building intelligent web applications.

---

## ✨ Features

- 🔗 **OpenAI GPT Integration** – Communicate with OpenAI’s powerful language model.
- 💬 **Web Chat Interface** – Simple HTML-based frontend using Flask's templating.
- 🔐 **.env File Support** – Store and use API keys securely.
- 🔄 **Stateless Requests** – Each message is handled independently for simplicity.
- 💻 **Easily Extendable** – Add context memory, user authentication, or UI themes.

---

## 🛠️ Tech Stack

| Layer       | Technology            |
|-------------|------------------------|
| Frontend    | HTML, CSS              |
| Backend     | Python, Flask          |
| AI Model    | OpenAI GPT (via API)   |
| Environment | dotenv (.env support)  |

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.8+
- An OpenAI API Key (get it from https://platform.openai.com/account/api-keys)

### Installation

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/chatbot.git
cd chatbot
```

2. **Create a Virtual Environment**

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. **Install Dependencies**

```bash
pip install -r requirements.txt
```

4. **Configure the Environment Variables**

Create a `.env` file in the root directory and add your OpenAI key:



---

### Running the App

```bash
python app.py
```

Once running, open your browser and visit:  
`http://127.0.0.1:5000/`

---

## 💡 Usage

- Enter a message into the input box.
- Submit the form to receive a GPT-generated response.
- Responses are processed via OpenAI’s API in real-time.

---

## 📁 Project Structure

```
Chatbot/
├── app.py               # Main Flask application
├── .env                 # Environment variables (ignored by Git)
├── templates/
│   └── index.html       # Chat UI
├── static/              # (Optional) Static assets
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---



## 🤝 Contributing

Pull requests are welcome! Feel free to suggest improvements or submit issues.

1. Fork the project
2. Create your feature branch: `git checkout -b feature/feature-name`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature/feature-name`
5. Open a pull request

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- [OpenAI](https://openai.com/) for their GPT API
- [Flask](https://flask.palletsprojects.com/) for the web framework