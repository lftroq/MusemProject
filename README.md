# 🎵 Musem Project — Emotion-Aware Music Recommendation Chatbot 🤖

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![Librosa](https://img.shields.io/badge/Audio-Librosa-orange.svg)](https://librosa.org/)
[![SVM](https://img.shields.io/badge/Model-SVM-green.svg)](https://scikit-learn.org/)
[![Gradio](https://img.shields.io/badge/UI-Gradio-yellow.svg)](https://gradio.app/)
[![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)](LICENSE)

---

## 🧩 Overview
**Musem (Music + Emotion)** is an AI-powered chatbot that recommends songs based on the user’s **current emotion**, detected directly from their **voice**.  
By analyzing vocal features, Musem suggests music that helps users **manage emotions**, **relax**, or **uplift** their mood.

---

## ✨ Features
- 🎙 **Voice Emotion Detection:**  
  Detects user emotion using an **SVM model** trained on the **RAVDESS Emotional Speech Audio** dataset.

- 🎧 **Personalized Music Recommendation:**  
  Suggests songs from **Spotify mood data**, categorized by features like *valence*, *energy*, and *tempo*.

- 💬 **Interactive Chatbot:**  
  Built with **Gradio**, supporting both **text** and **voice** conversations.

- 🧠 **AI Reasoning Engine:**  
  Integrated with **Gemini AI + RAG** for emotion-aware contextual responses.

- 🔊 **Natural Voice Interaction:**  
  Uses `SpeechRecognition` for voice input and `gTTS` (Google Text-to-Speech) for output.

---

## ⚙️ Technical Summary
| Component | Description |
|------------|--------------|
| **Feature Extraction** | MFCCs via `librosa` |
| **Model** | Support Vector Machine (RBF kernel) |
| **Optimization** | GridSearchCV with Stratified K-Fold |
| **Metrics** | Precision, Recall, F1, Accuracy |
| **Accuracy** | ≈ 71% (Macro-F1: 0.70) |
| **Frontend** | Gradio Web Interface |
| **Deployment** | Localhost / Web Demo |

---

## 🔐 Ethics & Privacy
Musem addresses the ethical challenges of AI in mental-health applications:

- 🔒 **Data Privacy:**  
  Anonymizes user data and minimizes personal data collection.

- ⚖️ **Transparency:**  
  Clearly informs users that Musem is an **AI assistant**, *not a therapist*.

- 🧩 **Bias Mitigation:**  
  Ensures diverse, balanced datasets and regular audits for bias.

- 🚨 **Safety Measures:**  
  Provides disclaimers and emergency guidance for sensitive user contexts.

---

## 🚀 Future Development
- Train on **larger multilingual datasets** for emotion recognition.
- Integrate **NLP emotion understanding** from speech content.
- Replace rule-based music recommendation with a **deep learning recommender**.
- Deploy with **Flask** for improved UI/UX and chat history.
- Extend recommendations to **movies, books, and activities**.

---

## 🧑‍💻 Team
| Name | Student ID |
|------|-------------|
| **Lê Phú Trọng** | BDAI-011 |
| **Phạm Văn Minh Phúc** | BDAI-021 |
| **Vũ Gia Bảo** | BDAI-045 |
| **Nguyễn Vũ An Vượng** | BDAI-055 |
| **Nguyễn Phạm Đức Huy** | BDAI-056 |

📍 *Ho Chi Minh City, September 2025*

---

## 📚 References
1. McFee et al. (2015). *Audio and Music Signal Analysis in Python (Librosa)*  
2. Davis & Mermelstein (1980). *Parametric Representations for Word Recognition*  
3. Scherer (2003). *Vocal Communication of Emotion*  
4. Juslin & Laukka (2003). *Emotion in Music and Vocal Expression*  
5. Banse & Scherer (1996). *Acoustic Profiles in Vocal Emotion Expression*

---

> 🎶 *Musem — Where AI Listens, Understands, and Plays Your Emotions.*
