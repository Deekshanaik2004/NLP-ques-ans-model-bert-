# NLP-ques-ans-model-bert-
##  Project Overview

This project is a web application that allows users to input a paragraph and ask questions related to that paragraph. It uses a pre-trained **BERT model** from Hugging Face to find the most probable answer.

###  Technologies Used
- Python 3.9+
- Streamlit
- Hugging Face Transformers
- Pre-trained Model: `bert-large-uncased-whole-word-masking-finetuned-squad`

---

##  Project Structure
question_answering_app/
├── qa_app.py
├── requirements.txt
├── README.md


---

## 💻 Installation & Running Instructions

1 Clone the Repository
git clone https://github.com/Deekshanaik2004/question_answering_app.git
cd question_answering_app

2 Set Up Virtual Environment
python -m venv venv
venv\Scripts\activate  # For Windows
source venv/bin/activate  # For Mac/Linux

3 Install Dependencies
pip install -r requirements.txt

4 Run the Application
streamlit run qa_app.py
Open your browser and visit:
http://localhost:8501

 Notes
The first load may take several minutes due to model download (~1.3 GB).

Works entirely locally — no OpenAI API required.

 Author
Deeksha Naik

GitHub: https://github.com/Deekshanaik2004

