# 🏥 MediSuite AI Agent

An AI-powered healthcare assistant that automates hospital and insurance claim workflows by extracting patient information, suggesting medical codes, and generating CMS-1500 claim forms. The system reduces manual paperwork, improves coding accuracy, and accelerates insurance claim processing.

---

## 🚀 Features

### 💬 AI Chat Interface
- Interactive chatbot for healthcare professionals
- Real-time AI responses
- Guided and summary conversation modes
- Session management and progress tracking
- User-friendly interface with notifications

### 📄 Intelligent Document Processing
- Upload PDF medical reports
- Process JPG and PNG images
- OCR-based text extraction using Tesseract
- Automatic patient information extraction
- Clinical note analysis

### 🩺 Medical Coding Assistant
- ICD-10 diagnosis code suggestions
- CPT-4 procedure code recommendations
- Fuzzy matching for accurate code prediction
- Confidence scoring for suggested codes
- Code verification before claim submission

### 👤 Patient Information Management
- Structured patient data collection
- Insurance details management
- Input validation
- Secure workflow handling

### 📑 Insurance Claim Generation
- Automated CMS-1500 form creation
- PDF claim generation
- Built-in PDF preview
- Export completed claim forms

### ⚙️ Workflow Automation
- Conversation state management
- Error handling and recovery
- Multi-step guided workflow
- End-to-end claim processing

---

# 🛠 Tech Stack

### Frontend
- Python Tkinter

### Backend
- Python

### AI & NLP
- OpenAI API / LLM
- Prompt Engineering

### OCR
- Tesseract OCR
- Poppler

### Document Processing
- PyPDF2
- pdf2image
- Pillow

### Medical Coding
- ICD-10 Database
- CPT-4 Lookup
- Fuzzy Matching Algorithms

---

# 📂 Project Workflow

```
Medical Report
       │
       ▼
Document Upload
       │
       ▼
OCR & Text Extraction
       │
       ▼
Patient Information Extraction
       │
       ▼
AI Medical Analysis
       │
       ▼
ICD-10 & CPT-4 Code Suggestions
       │
       ▼
Claim Verification
       │
       ▼
CMS-1500 PDF Generation
```

---

# 📌 Key Features

- AI-powered medical assistant
- Automated insurance workflow
- Medical document understanding
- OCR-enabled report processing
- Intelligent ICD-10 & CPT-4 coding
- CMS-1500 claim generation
- Multi-step guided interaction
- Cross-platform PDF support

---

# 💻 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/MediSuite-AI-Agent.git

cd MediSuite-AI-Agent
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Install System Dependencies

### Tesseract OCR

Download and install:
https://github.com/UB-Mannheim/tesseract/wiki

### Poppler

Download:
https://blog.alivate.com.au/poppler-windows/

Update the paths inside `Agent.py`

```python
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'

POPPLER_PATH = r'C:\Program Files\poppler\Library\bin'
```

---

# ▶️ Run the Project

```bash
python app.py
```

---

# 📸 Usage

### Guided Mode
- Step-by-step patient data entry
- AI-assisted diagnosis coding
- Claim generation

### Summary Mode
- Process complete patient information at once
- Generate claim instantly

### Document Upload
- Upload medical reports
- Extract patient information
- Suggest diagnosis codes
- Generate insurance claims

---

# 📋 Use Cases

## Hospital Staff
- Patient registration
- Diagnosis coding
- Claim preparation

## Insurance Companies
- Automated claim verification
- Faster processing
- Reduced manual effort

## Clinics
- Medical record digitization
- Insurance form generation

---

# 🎯 Future Improvements

- Voice-enabled medical assistant
- Multi-language support
- HL7/FHIR integration
- Electronic Health Record (EHR) integration
- AI-based fraud detection
- Doctor dashboard
- Cloud deployment
- Role-based authentication

---

# 📊 Project Highlights

✅ OCR-powered document extraction

✅ AI-assisted medical coding

✅ Automated insurance claim generation

✅ ICD-10 & CPT-4 support

✅ CMS-1500 PDF creation

✅ Interactive AI chatbot

---

# 📜 License

This project is licensed under the MIT License.
