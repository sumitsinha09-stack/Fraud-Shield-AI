# 🛡️ Fraud Shield AI

**Unified Scam Detection Platform** — Real-time threat analysis across SMS, Email, URLs, Voice, and Files with AI-powered deepfake detection and human-in-the-loop feedback.

## 🚀 Features

### Multi-Modal Detection
- **Text Analysis** — SMS/Email scam detection with NLP intent classification, stylometry analysis, and semantic similarity
- **URL Analysis** — Heuristic checks, SSL validation, WHOIS lookup, sandbox execution, and VirusTotal integration
- **Voice Detection** — Acoustic anomaly detection, deepfake detection, and speech-to-text analysis
- **Video Detection** — Temporal consistency analysis, facial artifact detection, and AV sync verification
- **File Analysis** — YARA rules, ClamAV integration, and VirusTotal hash lookup
- **Email Analysis** — IMAP integration, SPF/DKIM/DMARC header validation, and phishing detection

### Security & Intelligence
- **Threat Scoring** — Unified 0-100 scoring engine with fidelity ranking across all detection vectors
- **Vector Database** — ChromaDB semantic search with 55+ seeded known scam patterns
- **Prompt Injection Protection** — Shadow Guard middleware blocks malicious prompt injection attempts
- **DLP (Data Loss Prevention)** — Blocks sensitive data (API keys, credit cards, SSNs) from leaking in responses
- **Human-in-the-Loop Feedback** — Learn from user verdicts to continuously improve accuracy

### Frontend Experience
- **Interactive Dashboard** — Analyze suspicious content in real-time
- **Multiple Input Modes** — Text, URL, file upload, voice recording, and email inbox scanning
- **Live Threat Visualization** — Animated threat score ring with severity indicators
- **Feedback Loop** — Submit verdicts to improve model accuracy
- **Status Monitoring** — API health check with live connection status

## 📋 Requirements

### Backend
- Python 3.9+
- FastAPI & Uvicorn
- ChromaDB (vector database)
- Anthropic API (Claude)
- Groq API (for text analysis)
- Playwright (sandbox browser)
- Faster-Whisper (speech-to-text)

### Frontend
- Node.js 18+
- Next.js 16+
- React 19+
- Tailwind CSS

## 🔧 Installation

### Backend Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/sumitsinha09-stack/Fraud-Shield-AI.git
   cd Fraud-Shield-AI
