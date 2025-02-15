## 🚀 LLM-Powered Automation Agent
Welcome to the LLM-Powered Automation Agent! This advanced automation tool utilizes cutting-edge natural language processing and large language model (LLM) technology to efficiently handle a wide range of tasks.
---

## 🌟 Key Features
🤖 Intelligent Task Interpretation: Utilizes GPT-4o-Mini to accurately parse and understand tasks for optimal execution.
🔒 Safe File Handling: Guarantees secure processing of sensitive files, ensuring privacy and integrity.
⚡ Versatile Task Management: Capable of managing and executing a variety of tasks seamlessly, improving productivity.
🌐 API-Driven Execution: Leverages robust API integrations to perform tasks efficiently across different platforms.
---


## 📋 Prerequisites  
Make sure you have the following installed:  
- **Docker**: For containerization and deployment.  
- **AI Proxy Token**: Required for accessing LLM functionalities.  

---

## ⚙️ Installation & Run  


### 1. Install Dependencies  
```
pip install -r requirements.txt  
```

### 2. Setup Environment Variables  
### Create a .env file in the project root  
```
echo "AIPROXY_TOKEN=your_token_here" > .env  
```

### 3. Run Locally  
```
python run.py  
```

### 4. Using Docker  
### Build the image  
```
docker build -t llm-agent .  
```

### Run the container  
```
docker run --env-file .env -p 8000:8000 llm-agent  
```
