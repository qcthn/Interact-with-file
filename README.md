# HRIS AI Assistant 🤖

A powerful AI-powered HR assistant that revolutionizes CV processing and candidate evaluation through an intuitive web interface and robust API backend.

## 🚀 Key Features

- **Intelligent CV Processing**: Seamlessly extracts and analyzes information from multiple file formats:
  - PDF (✓)
  - DOCX (✓)
  - XLSX (✓)
  - PPTX (✓)
  - TXT (✓)

- **Advanced AI Analysis**: Leverages OpenAI's GPT-3.5 to:
  - Extract structured candidate information
  - Evaluate candidate strengths and weaknesses
  - Assess language proficiency
  - Provide intelligent responses to HR queries

- **Dual Interface**:
  - Interactive Streamlit Web UI for human-friendly interactions
  - Robust FastAPI backend for programmatic access

## 💡 Key Capabilities

- **Smart Information Extraction**: Automatically identifies and structures:
  - Personal Information
  - Skills & Competencies
  - Work Experience
  - Educational Background
  - Certifications
  - Language Proficiency
  - Strengths & Areas for Improvement

- **Interactive Chat**: Enables natural language conversations about candidate profiles
- **JSON Export**: Generates structured, machine-readable outputs
- **Multi-file Processing**: Handles batch CV processing efficiently

## 🛠️ Technical Stack

- **Frontend**: Streamlit
- **Backend**: FastAPI
- **AI Integration**: OpenAI GPT-3.5
- **File Processing**:
  - pdfplumber
  - python-docx
  - pandas
  - python-pptx

## 🚀 Getting Started

1. **Install Dependencies**:
```bash
pip install -r requirements.txt
```

2. **Set Environment Variables**:
```bash
export OPENAI_API_KEY="your-api-key"
```

3. **Launch the Application**:
```bash
python main.py
```

The application will start:
- FastAPI server on port 8080
- Streamlit interface on port 8050

## 🔌 API Endpoints

- `GET /`: Health check endpoint
- `POST /upload-file/`: Upload and process CV files
- `GET /get-extract-text/`: Retrieve extracted text content
- `GET /get-json/`: Generate structured JSON from CV
- `POST /ask-question/`: Query the AI about specific CVs
- `DELETE /clean/`: Clear temporary files

## 🎯 Use Cases

- **HR Departments**: Streamline candidate screening process
- **Recruitment Agencies**: Process multiple CVs efficiently
- **Career Counselors**: Analyze candidate profiles comprehensively
- **Job Seekers**: Get AI-powered feedback on their CVs

## 🔒 Security Features

- API key authentication
- Secure file handling
- Temporary file cleanup
- Protected endpoints

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- OpenAI for providing the GPT-3.5 API
- The Streamlit team for their excellent web framework
- FastAPI team for the robust API framework

---

Built with ❤️ for HR professionals and recruiters worldwide
