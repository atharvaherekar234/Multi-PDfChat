# Multi-PDfChat
# Chat with Multiple PDFs

## 📖 About
This is a Streamlit-based web application that allows users to upload multiple PDF documents and ask questions about their content. The app utilizes LangChain, FAISS for vector storage, and Google Generative AI for intelligent responses.

## 🚀 Features
- **Multi-PDF Support**: Upload multiple PDFs and extract text from them.
- **AI-Powered Chat**: Ask questions and get relevant answers using Google Generative AI.
- **User Authentication**: Secure login/logout using Streamlit Authenticator.
- **Memory Retention**: Keeps track of chat history for a seamless experience.

## 🛠️ Installation

### **1. Clone the Repository**
```sh
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### **2. Create a Virtual Environment & Activate**
```sh
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

### **3. Install Dependencies**
```sh
pip install -r requirements.txt
```

### **4. Set Up Environment Variables**
Create a `.env` file in the project root and add your Google API key:
```sh
GEMINI_API_KEY=your_google_api_key
```

### **5. Run the Application**
```sh
streamlit run app.py
```

## 📂 Project Structure
```
📁 your-repo-name/
│-- app.py               # Main application file
│-- requirements.txt     # List of dependencies
│-- .env                 # API keys and environment variables
│-- htmlTemplates.py     # HTML templates for chat
│-- hashed_pw.pkl        # Pickle file for storing hashed passwords
```

## 🌟 Future Improvements
- Add support for more AI models.
- Enhance UI/UX with better styling.
- Implement a database for storing user chat history.

## 📜 License
This project is open-source and available under the MIT License.

## 🤝 Contributing
Feel free to contribute! Fork the repository and submit a pull request.


