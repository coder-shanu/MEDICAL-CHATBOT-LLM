
---

# **Medical Chatbot using LLMs, LangChain, Pinecone, Flask & AWS**

An **AI-powered medical chatbot** built using **Large Language Models (LLMs)**, **LangChain**, **Pinecone**, **Flask**, and **AWS** for providing real-time medical assistance, answering health-related queries, and delivering accurate, context-aware responses.

---

## **Features**

✅ **LLM-based Chat** – Utilizes advanced language models for natural and human-like conversations.
✅ **LangChain Integration** – Manages conversational flow and context across multiple interactions.
✅ **Vector Database with Pinecone** – Stores and retrieves relevant medical information efficiently.
✅ **Flask Backend** – Lightweight and scalable backend for handling user requests and responses.
✅ **AWS Deployment** – Deployed on AWS for reliability and scalability.
✅ **Secure & Privacy-Focused** – Ensures user data protection and compliance with healthcare standards.
✅ **User-Friendly Interface** – Simple and responsive chat UI for smooth interaction.

---

## **Tech Stack**

* **Programming Language:** Python
* **Framework:** Flask
* **AI/ML:** LLMs (OpenAI/GPT), LangChain
* **Database:** Pinecone (Vector DB)
* **Deployment:** AWS (EC2/S3)
* **Frontend:** HTML, CSS, JavaScript (for chat interface)

---

## **System Architecture**

```
User -> Chat UI -> Flask API -> LLM (via LangChain) -> Pinecone DB -> Response -> User
```

---

## **Installation & Setup**

### **Prerequisites**

* Python 3.9+
* Pinecone API Key
* OpenAI API Key
* AWS Account for deployment

---



### **2. Create Virtual Environment**

```bash
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
```

### **3. Install Dependencies**

```bash
pip install -r requirements.txt
```

### **4. Set Environment Variables**

Create a `.env` file and add:

```
OPENAI_API_KEY=your_openai_api_key
PINECONE_API_KEY=your_pinecone_api_key
AWS_ACCESS_KEY=your_aws_key
AWS_SECRET_KEY=your_aws_secret
```

### **5. Run the Flask App**

```bash
python app.py
```

The app will run on `http://127.0.0.1:5000/`.

---

## **Deployment on AWS**

* Use **AWS EC2** instance for hosting the Flask backend.
* Configure **Nginx** or **Gunicorn** for production.
* Optionally, use **AWS S3** for static assets and **AWS RDS** if needed.

---

## **Usage**

* Open the chat interface in your browser.
* Type any health-related query.
* The chatbot responds with context-aware and reliable answers.

---

## **Future Enhancements**

* ✅ Add **voice input and output** for hands-free interaction.
* ✅ Implement **multi-language support**.
* ✅ Add **symptom checker** and **doctor recommendation system**.
* ✅ Integrate **medical image analysis** (X-rays, reports).

---



  
