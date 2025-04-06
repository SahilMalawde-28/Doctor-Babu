# 🩺 AI-Powered WhatsApp Healthcare Assistant – *"Doctor Babu / Swasthiq"*

> **Bringing Healthcare to Every Village – One Chat at a Time**

---

## 📌 Overview

In regions where access to medical services is limited, our solution acts as a **virtual healthcare assistant** using **WhatsApp and a lightweight mobile app**. It offers medical guidance, symptom analysis, report tracking, and government scheme support — all powered by **open-source AI** and designed for **low-connectivity** environments.

---

## 🚀 Key Features

- 💬 **WhatsApp Chatbot**  
  Works smoothly on low-bandwidth networks to accept symptoms via text, voice, or image.

- 🧠 **AI Symptom Analysis**  
  Uses NLP and medical models like **MedSpacy** and **BioBERT** to understand user inputs and suggest actions.

- 📈 **User Health Profile**  
  Medical records, previous reports, and prescriptions organized and accessible via chatbot or mobile app.

- 🏥 **Emergency Triage & Referrals**  
  Detects critical symptoms and connects users to nearby hospitals or teleconsultation options.

- 🛡️ **Government Scheme Integration**  
  Auto-recommends health schemes users are eligible for, based on their case.

- 📱 **Companion Mobile App**  
  For deeper functionality like full medical history, syncing offline data, and reminders — in multiple Indian languages.

---

## 🧠 Open-Source Tech Stack

| Purpose                  | Tools / Libraries Used                             |
|--------------------------|----------------------------------------------------|
| 🗣️ Speech to Text        | [Vosk](https://alphacephei.com/vosk/)               |
| 🧾 NLP for Symptoms      | [spaCy](https://spacy.io/), [MedSpacy](https://github.com/medspacy/medspacy), [BioBERT](https://github.com/dmis-lab/biobert) |
| 💡 Chatbot Engine        | [Gemini API / OpenRouter]                          |
| 🌐 Backend API           | Flask + Firebase                                   |
| ☁️ Cloud Hosting         | Firebase (Firestore, Storage), GCP or Render       |

---

## 🗂️ Datasets Used

- **Medical Mentions & Symptom Mapping**: Publicly available datasets (e.g., MedMentions, SLR)
- **Speech Inputs**: Real-time voice inputs from users using Vosk
- **User Data**: Encrypted and stored securely on Firebase; includes feedback and usage analytics

---

## 💡 Why This Matters

> *"Healthcare shouldn't be a luxury. With just a simple chat, we aim to save lives in India's most underserved regions."*

This solution is:
- 🧑‍⚕️ **Inclusive** – Built for users with no digital literacy.
- 🛰️ **Resilient** – Works on low internet and basic smartphones.
- 📱 **Scalable** – Supports both chatbot and app interactions.

---

## 🛠️ Setup & Installation

Coming Soon – Deployment-ready instructions to integrate with WhatsApp Business API and Firebase.

---

## 🌟 Star this Repo if you believe tech can save lives!

