# **🔍 Skill Extraction from Job Descriptions using NLP and BERT**

## **📌 Overview**  
This project leverages **Natural Language Processing (NLP)** and **BERT-based Named Entity Recognition (NER)** to **extract and classify skills** from job descriptions. The goal is to **automate skill identification** by recognizing **soft skills** and **technical skills** in job postings using **BIO-tagging** and a **fine-tuned BERT model**

---

## **🚀 Features**  

✔ **Automated Skill Extraction** – Detects both **technical** and **soft skills** in job descriptions  
✔ **Fine-tuned BERT Model** – Optimized for **Named Entity Recognition (NER)** on job-related text  
✔ **Comprehensive Skills Taxonomy** – Incorporates **O*NET skills database** and **web-scraped job postings**  
✔ **Intelligent Matching** – Recognizes **synonyms and variations** (e.g., "Machine Learning Engineer" → "ML Engineer")  

---

## **📊 Dataset Details**  

- **📂 Job Descriptions Dataset** – 187,853 **web-scraped job descriptions**  
- **🆔 Unique Identification** – Each job description is assigned a **Job ID**  
- **📝 Data Columns**:  
  - **Job Description** – Detailed text about each role  
  - **Skills** – Extracted skills required for the job  

- **🗂 Skills Database** – 8,904 **skills extracted from onetonline.org**, including:  
  - **35 Soft Skills** (e.g., leadership, communication)  
  - **8,869 Technical Skills** (e.g., Python, Kubernetes)  

---

## **📌 Model Approach**  

1️⃣ **Dataset Annotation** – BIO-tagging applied to **job descriptions**.  
2️⃣ **NER Model Training** – Fine-tune **BERT** for skill entity recognition.  
3️⃣ **Cross-Validation** – Ensure model reliability using **k-fold validation**.  
4️⃣ **Evaluation Metrics** – Performance measured using **Precision, Recall, F1-Score, and AUC-ROC**.  

---

## **🛠 Technology Stack**  

| **Component**  | **Technology** |
|---------------|----------------|
| **Language** | Python |
| **Frameworks** | TensorFlow, PyTorch, Hugging Face Transformers |
| **Data Processing** | Pandas, NumPy, NLTK, SpaCy |
| **Model Architecture** | BERT (Fine-Tuned for NER) |
| **Evaluation Metrics** | Precision, Recall, F1 Score, AUC-ROC |
| **Dataset** | Web-Scraped Job Descriptions + O*NET |

---

## **📥 Installation & Usage**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/tabishkhan72/Skill-Extraction-NLP-BERT.git
cd Skill-Extraction-NLP-BERT
```

### **2️⃣ Install Dependencies**  
Ensure Python **3.8+** is installed, then run:  
```bash
pip install -r requirements.txt
```

### **3️⃣ Train the Model**  
```bash
python train_ner.py
```

### **4️⃣ Run Skill Extraction**  
To extract skills from a sample job description:  
```bash
python extract_skills.py --input "Senior Data Scientist with expertise in Python and Deep Learning."
```

---

## **📊 Future Enhancements**  

✅ Improve model performance using **Transformer-based architectures (RoBERTa, DistilBERT)**.  
✅ Introduce **self-learning mechanisms** for continuous model updates.  
✅ Expand dataset for **more diverse industry-specific skills**.  
✅ Deploy as an **API** for integration with HR & recruitment platforms.  

---
