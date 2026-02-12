# Phish-Guard-Portfolio.
Phishing Email Analyzer is a standalone desktop application that helps identify phishing attempts through comprehensive email analysis. Built with Python and PySide6, it provides a professional interface for analyzing email headers, URLs, and content patterns to generate risk scores and security recommendations.
Purpose: Defensive cybersecurity tool for security awareness training, email triage, and threat detection education.
Developer: ABDULLAHI ISSACK MOHAMED

 Features:
🔍 Comprehensive Email Analysis

Header Authentication: SPF/DKIM verification, sender validation, routing analysis
URL Detection: Typosquatting, IP addresses, suspicious TLDs, link shorteners
Content Scanning: 30+ regex-based phishing patterns (urgency, threats, credential requests)
Risk Scoring: 0-100 weighted scoring system with detailed explanations

🎨 Professional User Interface

Modern Qt-based desktop application
Dual input modes: .eml file upload or raw email paste
Color-coded risk visualization (Low/Medium/High)
Tabbed results display (Summary, Findings, Recommendations, Details)
Real-time analysis with progress indicators

🔐 Security Intelligence

Sender/Return-Path mismatch detection
Reply-To inconsistency flagging
Free email provider identification
Generic greeting detection
Social engineering pattern recognition
Malicious URL characteristics analysis

📦 Deployment Ready

Standalone executable (.exe) generation
No external API dependencies (100% offline)
Cross-platform Python source code
Comprehensive documentation
Sample test emails included

