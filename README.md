# AI-ML-Task-for-NLTI
Certainly! Here’s a structured **README.md** file with steps for implementing both tasks.

---

# AI/ML-Based Mentor & Chatbot System  

## Overview  
This project aims to enhance **mentorship and engagement** for law aspirants preparing for CLAT and other entrance exams. It consists of two key tasks:  

- **Task 1:** Personalized Mentor Recommendation System  
- **Task 2:** Chatbot for Legal Exam Queries  

## Installation & Setup  
### Step 1: Clone the Repository  
```bash
git clone <your-repo-url>
cd <your-repo-folder>
```
### Step 2: Install Dependencies  
```bash
pip install pandas scikit-learn flask nltk spacy
```

---

## Task 1: Personalized Mentor Recommendation System  
### Step 1: Load Aspirant and Mentor Data  
- Define **aspirant profiles** with attributes like preferred subjects, target colleges, and learning style.  
- Define **mentor profiles** with expertise areas, alma mater, and teaching style.  

### Step 2: Process Feature Data  
- Convert text-based attributes using **TF-IDF vectorization**.  
- Normalize learning and teaching styles for compatibility.  

### Step 3: Compute Similarity & Recommend Mentors  
- Use **cosine similarity** to measure aspirant-mentor compatibility.  
- Extract **top 3 mentors** for each aspirant based on similarity scores.  

### Step 4: Implement Feedback System  
- Gather user ratings on mentor recommendations.  
- Adjust weights dynamically based on user feedback for better future recommendations.  

---

## Task 2: Chatbot for Legal Exam Queries  
### Step 1: Build a Knowledge Base  
- Collect frequently asked CLAT-related queries and answers.  
- Store data in structured format for searchability.  

### Step 2: Develop Query Processing Logic  
- Use **keyword-based search** or **NLP techniques** (spaCy/NLTK) for response generation.  
- Identify relevant knowledge base entries for each user query.  

### Step 3: Implement Chatbot Interface  
- Develop a simple **Flask/Streamlit app** to handle user queries.  
- Provide conversational responses based on query matching.  

### Step 4: Scale the Chatbot  
- Integrate **GPT-based models** for improved responses.  
- Fine-tune on CLAT-specific data for enhanced query accuracy.  

---

## Next Steps  
- Improve **recommendation accuracy** using real user feedback.  
- Expand chatbot capabilities for **better legal exam support**.  
- Deploy both systems as a **web application** for easy access.  

---

## License  
This project is open-source and can be modified for further improvements.  

---

This README provides a structured guide to implementing both tasks. Let me know if you need any modifications! 🚀
