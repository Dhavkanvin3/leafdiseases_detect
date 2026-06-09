# leafdiseases_detect
FastAPI Streamlit Python Groq 

An enterprise-grade AI-powered leaf disease detection system featuring a dual-interface architecture: a FastAPI backend service and an interactive Streamlit web application. Built with Meta's Llama Vision models via Groq API, this system provides accurate disease identification, severity assessment, and actionable treatment recommendations for agricultural and horticultural applications

Experience the power of AI-driven plant health analysis in action

🎯 Key Features
🎯 Core Capabilities
🔍 Advanced Disease Detection: Identifies 500+ plant diseases across multiple categories (fungal, bacterial, viral, pest-related, nutrient deficiencies)
📊 Precision Severity Assessment: AI-powered classification of disease severity levels (mild, moderate, severe)
**High-Confidence Scoring** : Provides confidence percentages (0-100%) with advanced uncertainty quantification
💡 Expert Treatment Recommendations: Evidence-based, actionable treatment protocols tailored to specific diseases
📋 Comprehensive Symptom Analysis: Detailed visual symptom identification with causal relationship mapping
⚡ Real-time Processing: Optimized inference pipeline with sub-5-second response times
🏗️ Architecture Components
FastAPI Backend (app.py): RESTful API service with automatic OpenAPI documentation
Streamlit Frontend (main.py): Interactive web interface with modern UI/UX design
Core AI Engine (Leaf Disease/main.py): Advanced disease detection engine powered by Meta Llama Vision
Utility Layer (utils.py): Image processing and data transformation utilities
Cloud Deployment: Production-ready with Vercel integration and scalable architecture
🏗️ Project Architecture
Directory Structure
Main Application Components:

🚀 main.py - Streamlit Web Application with interactive UI components, real-time image preview, results visualization, and modern CSS styling
🔧 app.py - FastAPI Backend Service with RESTful API endpoints, file upload handling, error management, and JSON response formatting
🧠 Leaf Disease/main.py - Core AI Detection Engine containing the LeafDiseaseDetector class, DiseaseAnalysisResult dataclass, Groq API integration, base64 image processing, response parsing and comprehensive error handling
Supporting Files:

🛠️ utils.py - Image processing utilities and helper functions
🧪 test_api.py - Comprehensive API testing suite
📋 requirements.txt - Python dependencies and package versions
⚙️ vercel.json - Deployment configuration for cloud platforms
📁 Media/ - Sample test images for development and testing
Core Module: Leaf Disease/main.py
The heart of the system, featuring the LeafDiseaseDetector Class which provides advanced AI-powered leaf disease detection using Groq's Llama Vision models. This class supports multi-format image input (JPEG, PNG, WebP, BMP, TIFF), automatic base64 encoding, structured JSON output with comprehensive disease information, robust error handling and response validation, plus configurable AI model parameters.

The DiseaseAnalysisResult DataClass serves as a structured container for disease analysis results, including boolean detection status, specific disease identification, category classification, severity assessment levels, AI confidence scores (0-100%), observable symptom lists, environmental and biological factors, evidence-based treatment recommendationsspecific disease identification, category classification, severity assessment levels, AI confidence scores (0-100%), observable symptom lists, environmental and biological factors, evidence-based treatment recommendations, and ISO 8601 timestamps.
