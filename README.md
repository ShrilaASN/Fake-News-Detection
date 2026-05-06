# 🛡️ TruthGuard  
### AI-Powered Fake News Detection System  

<p align="left">

![AI](https://img.shields.io/badge/AI-NLP-blue?style=for-the-badge)
![Frontend](https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react)
![Backend](https://img.shields.io/badge/Backend-Python-yellow?style=for-the-badge&logo=python)
![Project](https://img.shields.io/badge/Type-Hackathon-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

</p>

---

> **TruthGuard is an AI-powered system that detects fake news in real time by analyzing text and URLs, helping users make informed decisions and combat misinformation.**

---

## 🧠 Overview  

Misinformation has become one of the most critical challenges in the digital era.  
TruthGuard addresses this problem by providing a fast, reliable, and accessible way to verify the credibility of news content using machine learning and natural language processing.

---

## ❗ Problem Statement  

### AI/ML Domain- Automated Fake News Detection:
Develop a natural language processing model to classify and detect misleading or falseinformation in digital news content

---

## 💡 Solution  

TruthGuard leverages **AI + NLP models** to classify news as:

- ✅ **Real**
- ❌ **Fake**

Along with:
- Confidence score  
- Explanation of prediction  
- Detection of suspicious language  

---

## ✨ Key Features  

### Core Features
- Text-based fake news detection  
- URL credibility analysis  
- Confidence scoring  
- Highlighting misleading phrases  
- Fast and intuitive user interface  

### Extended Features
- Source credibility checker  
- Image manipulation detection *(planned)*  
- Multilingual support *(planned)*  
- History tracking  

---

## 🏗️ Tech Stack  

| Layer        | Technology |
|-------------|-----------|
| Frontend     | React, HTML, CSS, JavaScript |
| Backend      | Python (Flask / FastAPI) |
| AI/ML        | Logistic Regression, LSTM, BERT |
| Libraries    | scikit-learn, TensorFlow / PyTorch |
| Database     | MongoDB / Firebase |
| APIs         | News API, Google Fact Check API |

---

## 🔄 System Workflow  

1. User inputs text or URL  
2. Backend receives request  
3. NLP model processes content  
4. Prediction generated  
5. Results displayed with confidence and explanation  
6. Data optionally stored for history  

---

## 🖥️ Demo  

🔗 *deployed link here*  
📸 <img width="1083" height="910" alt="image" src="https://github.com/user-attachments/assets/58c17851-4307-4fc8-9927-520988b748ca" />
<img width="1042" height="910" alt="image" src="https://github.com/user-attachments/assets/15399271-7a8d-4500-8c07-57138a64fa08" />
<img width="1050" height="906" alt="image" src="https://github.com/user-attachments/assets/a568e45f-b9bc-441f-b41b-fd32a9084e85" />
<img width="1014" height="819" alt="image" src="https://github.com/user-attachments/assets/025ed0b7-4340-4eb2-9a48-cbf4fa4e2b68" />
<img width="1040" height="453" alt="image" src="https://github.com/user-attachments/assets/fbc2cf37-0c43-44fc-a76d-40cb0fe6af2e" />
<img width="1048" height="850" alt="image" src="https://github.com/user-attachments/assets/834cdd0f-12ab-45c2-8fd4-c98a394f5e4c" />

---

## 📊 Sample Output  

```json
{
  "text": "Breaking: Aliens landed on Earth",
  "result": "Fake",
  "confidence": 95
}
