  # Crew AI Book Writing Project

## 📖 Overview
This project leverages **CrewAI** to create a collaborative book-writing system using multiple AI agents. The agents assist in various aspects of the writing process, including research, editing, and content generation. The system integrates **OpenAI GPT-3.5/4**, **Claude Haiku**, and **ChatGroq** models to enhance the writing workflow.

## 🚀 Features
- **📖 Expert Agent**: Conducts research, summarizes information, and provides subject matter expertise.
- **📝 Editor Agent**: Reviews book concepts, refines summaries, and ensures alignment with market trends.
- **✍️ Content Writer Agent**: Writes engaging and high-quality book chapters.
- **📚 Complete Writer Agent**: A specialized agent dedicated to full book writing.
- **🔍 PDF Search Tool Integration**: Extracts and retrieves information from PDF documents.

## 🛠️ Technologies Used
- **Python**
- **CrewAI** for agent management
- **LangChain** for LLM integration
- **OpenAI GPT-3.5/4, Claude Haiku, ChatGroq** models
- **PDFSearchTool** for extracting data from documents

## 📌 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone <repository_url>
cd crew-ai-book-writer
```

### 2️⃣ Install Dependencies
Ensure you have Python 3.8+ installed and install the required packages:
```bash
pip install crewai langchain-openai langchain-groq langchain-anthropic crewai-tools
```

### 3️⃣ Set Up API Keys
Export the necessary API keys for model access:
```bash
export GROQ_API_KEY='your_groq_api_key'
export OPENAI_API_KEY='your_openai_api_key'
export ANTHROPIC_API_KEY='your_anthropic_api_key'
```

### 4️⃣ Run the Script
Execute the script to initiate the book-writing agents:
```bash
python main.py
```

## 🏗️ Agents and Their Roles

### 1. 📘 Expert Agent
- Retrieves book-related information
- Creates a book pitch and summary
- Ensures factual accuracy

### 2. 🖋️ Editor Agent
- Refines book summaries and structure
- Aligns content with market trends
- Oversees the book-writing process

### 3. ✒️ Content Writer Agent
- Writes engaging and structured chapters
- Ensures high-quality content creation

### 4. 📜 Complete Writer Agent
- Handles the entire writing process end-to-end
- Creates full-length chapters based on input

## 📌 Future Enhancements
- Integration with **vector databases** for improved retrieval
- Support for **multiple book genres**
- **Cloud-based deployment** for scalability

## 👨‍💻 Author
Developed by **ANUJ**

Feel free to contribute and enhance this project!
