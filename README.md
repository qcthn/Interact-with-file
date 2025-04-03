# Interact-with-file
# 🚀 HRIS AI Assistant

A powerful AI-driven HR Information System that revolutionizes CV processing and ID card information extraction.

## ✨ Key Features

### 📄 Advanced CV Processing
- **Extracts** critical information from multiple CV formats:
  - PDF
  - DOCX
  - TXT
  - XLSX
  - PPTX
- **Analyzes** and **structures** CV data into organized JSON format
- **Identifies** key components:
  - Personal Information
  - Skills
  - Experience
  - Education
  - Certifications
  - Languages
  - Strengths & Weaknesses
- **Powers** intelligent conversations about CVs using GPT-3.5 Turbo
- **Enables** HR professionals to make data-driven hiring decisions

### 🪪 Smart ID Card Processing
- **Automates** information extraction from ID cards
- **Detects** and **extracts**:
  - ID Number
  - Full Name
  - Date of Birth
  - Gender
  - Nationality
  - Place of Origin
  - Residence Address
  - Expiration Date
- **Provides** instant visual verification
- **Generates** structured data output

### 💡 Intelligent Features
- **Real-time** chat interface with AI assistant
- **Multi-document** processing capability
- **Streamlined** JSON export functionality
- **Interactive** user interface with Streamlit
- **Robust** error handling and validation
- **Secure** API key management

## 🛠️ Technology Stack

### Backend
- FastAPI
- Uvicorn
- SQLAlchemy
- Python 3.10+

### Frontend
- Streamlit
- Pillow
- PDFPlumber
- Python-docx
- OpenAI GPT-3.5

### AI/ML
- OpenAI API
- Computer Vision
- Natural Language Processing

## 🚀 Getting Started

### Prerequisites
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt
```

### Running the Application
```bash
# Start the FastAPI backend
python run.py

# Access the application
Frontend: http://localhost:8070
API: http://localhost:8080
```

## 🔑 Configuration

1. Obtain an OpenAI API key
2. Configure environment variables:
```bash
PORT=8080
UPLOAD_FOLDER=uploads
```

## 🎯 Use Cases

- **HR Departments**: Streamline candidate screening process
- **Recruitment Agencies**: Process multiple applications efficiently
- **Identity Verification**: Quick and accurate ID card processing
- **Document Management**: Structured data extraction from various formats

## 🔒 Security Features

- Secure API key handling
- Temporary file management
- Protected file uploads
- Sanitized data processing

## 🌟 Benefits

- **Time Savings**: Reduces manual document processing by up to 90%
- **Accuracy**: Minimizes human error in data extraction
- **Efficiency**: Processes multiple documents simultaneously
- **Intelligence**: Provides AI-powered insights and analysis
- **Flexibility**: Supports multiple document formats
- **Scalability**: Handles growing document processing needs

## 📈 Future Enhancements

- [ ] Multi-language support
- [ ] Advanced document analysis
- [ ] Custom AI model training
- [ ] Batch processing capabilities
- [ ] Enhanced security features
- [ ] API integration options

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- OpenAI for GPT-3.5 API
- Streamlit for the amazing UI framework
- FastAPI for the robust backend

---

⭐ Star us on GitHub if this project helps you!
