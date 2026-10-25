# 🐍 PyTutor AI - Python Learning Assistant Chatbot

**PyTutor AI** adalah aplikasi chatbot interaktif berbasis *Large Language Model* (LLM) menggunakan integrasi **Google Gemini API** dan antarmuka **Streamlit**. Proyek ini dirancang sebagai *Education Bot* untuk membantu pemula mempelajari konsep dasar pemrograman Python secara terstruktur dan interaktif.

Proyek ini dibuat untuk memenuhi tugas **Final Project: LLM-Based Tools and Gemini API Integration for Data Scientists**.

## ✨ Fitur Utama & Parameter Kreatif
* **Use Case Spesifik (Education Bot):** Dikonfigurasi melalui *System Instruction* khusus agar berperan sebagai tutor pemrograman Python yang sabar dan edukatif.
* **Kustomisasi Gaya Bahasa:** Pengguna dapat memilih gaya penyampaian materi di *sidebar* (**Santai & Ramah** atau **Formal & Akademis**).
* **Manajemen Memori Percakapan (*Session State*):** Menyimpan konteks obrolan sebelumnya sehingga pengguna dapat berdiskusi secara berkelanjutan.
* **Auto-Fallback Model System:** Dilengkapi mekanisme pergantian model otomatis (*multi-model fallback*) untuk menjaga ketersediaan layanan ketika batas kuota (*rate limit*) harian pada satu model tercapai.

## 🛠️ Teknologi yang Digunakan
* **Bahasa Pemrograman:** Python 3.x
* **Framework UI:** Streamlit
* **Model AI / SDK:** Google Generative AI (`google-generativeai`)

## 🚀 Cara Menjalankan Aplikasi Secara Lokal
1. Instal pustaka yang dibutuhkan:
   `pip install -r requirements.txt`
2. Jalankan aplikasi Streamlit:
   `streamlit run app.py`
3. Masukkan **Gemini API Key** Anda pada kolom konfigurasi di *sidebar* sebelah kiri, pilih gaya bahasa, dan mulai percakapan.
