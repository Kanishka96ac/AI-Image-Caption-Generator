# AI Image Caption Generator (LLaVA)

This project uses the **LLaVA model** via Ollama to generate descriptive captions for uploaded images.

## 📌 Features

- **Vision-Language Model** (LLaVA) for image understanding
- **FastAPI** backend for processing images
- **Streamlit** frontend for an interactive UI
- Fully local processing via **Ollama**

## 🚀 How to Run

### 1️⃣ Setup Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 2️⃣ Pull LLaVA Model

Make sure Ollama is installed and running:

```bash
ollama pull llava
```

### 3️⃣ Start Backend

```bash
uvicorn backend.main:app --reload
```

### 4️⃣ Start Frontend

```bash
streamlit run frontend/app.py
```

### 5️⃣ Use the App

- Upload a PNG, JPG, or JPEG image
- Click **Generate Caption**
- Get an AI-generated description of the image

## 📂 Project Structure

```
image-caption-llava/
├── backend/
│   └── main.py
├── frontend/
│   └── app.py
├── requirements.txt
└── README.md
```

## 🛠 Tech Stack

- Python
- FastAPI
- Streamlit
- Ollama (LLaVA model)
- Pillow

---

## 🔗 Connect with Me

📧 kanishka96se@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/kanishka96/) | [GitHub](https://github.com/Kanishka96ac)
