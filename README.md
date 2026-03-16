# SIH1706
# Name: G.Ramanujam
# Reg.No: 212224240129

# Aim
To develop an AI-driven enterprise chatbot capable of assisting employees by answering organizational queries, processing documents, and improving overall workplace efficiency.

# Description
Develop a chatbot using deep learning and natural language processing techniques to accurately understand and respond to queries from employees of a large public sector organization.

 The chatbot should be capable of handling diverse questions related to HR policies, IT support, company events, and other organizational matters. (Hackathon students/teams to use publicly available sample information for HR Policy, IT Support, etc. available on internet.) Develop document processing capabilities for the chatbot to analyse and extract information from documents uploaded by employees.

This includes summarizing a document or extracting text (keyword information) from documents relevant to organizational needs. (Hackathon students/teams can use any 8 to 10 page document for demonstration). Ensure the chatbot architecture is scalable to handle minimum 5 users parallelly. This includes optimizing response time (Response Time should not exceed 5 seconds for any query unless there is a technical issue like connectivity, etc.) Enable 2FA (2 Factor Authentication – email id type) in the chatbot for enhancing the security level of the chatbot.

# Requirements

### **i)Hardware Requirements**
Processor: Intel i5 or higher
RAM: Minimum 8 GB
Storage: 10 GB free disk space

### **ii)Software Requirements**
Python 3.9+
Node.js (optional for frontend)
Git
Web browser

# System Architecture

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/be80a0d0-a60f-43bc-826b-cf3c97aea308" />

# Procedure

### **Step 1: Data Collection**

The first step in developing the Intelligent Enterprise Assistant is data collection. In this stage, publicly available datasets and documents are gathered to build the knowledge base of the chatbot. These documents include HR policy manuals, IT support guidelines, organizational procedures, and company event information. Collecting these resources helps the chatbot understand and respond accurately to employee queries related to organizational operations.

### **Step 2: Data Preprocessing**

After collecting the data, the next step is preprocessing the text to prepare it for machine learning models. This process includes tokenization, where the text is broken into smaller units called tokens. Stop-word removal eliminates commonly used words that do not contribute much meaning. Lemmatization is then applied to convert words into their base form. Finally, text embeddings are generated to transform the textual data into numerical representations that can be processed by NLP models.

### **Step 3: NLP Model Integration**

In this step, pretrained Natural Language Processing models are integrated into the system. Models such as BERT, GPT-based models, and Sentence Transformers are used to improve the chatbot's understanding of human language. These models help perform tasks such as identifying user intent, answering questions accurately, and conducting semantic searches within the knowledge base.

### **Step 4: Document Processing**

The system includes a document processing module that allows employees to upload documents such as HR manuals or organizational guidelines. The chatbot analyzes these documents by extracting text from PDF files, summarizing long documents, identifying important keywords, and answering questions related to the uploaded document. Tools such as PyPDF, LangChain, and HuggingFace summarization models are used to implement these capabilities.

### **Step 5: Chatbot Development**

In this stage, the chatbot functionality is developed. The chatbot is designed to understand employee queries using NLP techniques and retrieve relevant information from the knowledge base. It then generates responses in a conversational format, allowing employees to interact with the system easily and obtain information quickly.

### **Step 6: Two-Factor Authentication (2FA)**

To enhance security, the system implements Two-Factor Authentication. During login, the user enters their email address, and the system sends a One-Time Password (OTP) to the registered email. The user must enter this OTP to verify their identity. Once verified, access to the chatbot is granted, ensuring secure usage of the system.

### **Step 7: Language Filtering**

A language filtering mechanism is implemented to maintain professional communication within the system. The chatbot checks user inputs against a dictionary of prohibited words. If any inappropriate or offensive language is detected, the system blocks or filters the message to maintain a respectful communication environment.

### **Step 8: Performance Optimization**

The final step involves optimizing the system's performance. The chatbot architecture is designed to handle multiple users simultaneously while maintaining fast response times. The system ensures that at least five users can interact with the chatbot concurrently, and each query is answered within five seconds, ensuring efficiency and scalability.

# Output

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/0ebcb411-82b5-456c-a492-ddc3f27136de" />


The developed **Intelligent Enterprise Assistant Chatbot** successfully provides an AI-based solution to support employees in public sector organizations. The system allows users to interact through a web-based chat interface where they can ask questions related to HR policies, IT support, organizational procedures, and company events. The chatbot processes user queries using Natural Language Processing techniques and retrieves relevant information from the knowledge base to generate accurate responses.

The system also supports **document processing**, where employees can upload documents such as HR manuals or organizational reports. The chatbot extracts text from these documents, summarizes the content, identifies important keywords, and answers questions related to the uploaded documents. This helps employees quickly understand lengthy documents without manually reading them.

For security, the system implements **Two-Factor Authentication (2FA)** using email-based OTP verification, ensuring that only authorized users can access the chatbot. Additionally, a **language filtering mechanism** prevents the use of inappropriate or offensive words, maintaining professional communication within the system.

The chatbot architecture is designed to support **multiple users simultaneously**, handling at least five concurrent users while maintaining a response time of less than five seconds. Overall, the system improves organizational efficiency by providing quick access to information, reducing manual workload, and enhancing employee productivity.

# Result

The Intelligent Enterprise Assistant chatbot successfully provides secure, fast, and AI-powered responses to employee queries while supporting document processing and handling multiple users efficiently.
