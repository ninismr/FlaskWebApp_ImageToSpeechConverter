<p align="center">
  <img src="ihearyou.png" alt="I.HEAR.YOU Logo" width="200">
</p>

<h1 align="center">I.HEAR.YOU</h1>

<p align="center">
  <strong>A Web-Based Image-To-Speech Converter Application</strong><br>
  <em>Extracting and Converting Image Text into Speech Using Optical Character Recognition and Speech Synthesis with Translation Support</em>
</p>

<p align="center">
  🔹 Built with <strong>Flask</strong>, <strong>Tesseract OCR</strong>, <strong>gTTS</strong>, and <strong>Natural Language Processing</strong> 🔹
</p>



# 🗣️ I.HEAR.YOU - Image to Speech Converter  

**A Flask Web Application for Extracting and Converting Image Text into Speech with Translation Support**  

---

## 📌 Introduction  

In today's digital world, **text is everywhere**, from books and signs to online articles. However, **not everyone can easily access or understand written content**—whether due to visual impairment, language barriers, or reading difficulties. **I.HEAR.YOU** is a **Flask-based web application** designed to **bridge this gap by extracting text from images, translating it into different languages, and converting it into natural-sounding speech**.  

This project combines **Optical Character Recognition (OCR)** with **Text-to-Speech (TTS) technology**, allowing users to:  
✅ **Extract text** from an image with **high accuracy**  
✅ **Listen to the extracted text** in a human-like voice  
✅ **Translate the text** into multiple languages  
✅ **Hear and download the translated speech**  

Whether you need to **read a foreign sign, assist someone with a visual impairment, or simply want to listen to text instead of reading**, this application offers an **efficient and accessible** solution. Built with **Flask, Tesseract OCR, gTTS, and OpenCV**, it delivers a **lightweight yet powerful tool** for real-world use.    

### 🔍 **How It Works**  
1. **User uploads an image** containing text.  
2. The system **extracts the text** using **Tesseract OCR**.  
3. The extracted text is **converted into speech** using **gTTS (Google Text-to-Speech)**.  
4. Users can **translate the extracted text** into a selected language.  
5. The translated text is also **converted into speech** and can be **downloaded** as an audio file.  

This application is useful for:  
- **Visually impaired users** who need text read aloud  
- **Multilingual users** who want to **translate text and hear it in another language**  
- **Language learners** who want to practice pronunciation  

---

## 🌟 Features  

✔️ **Upload an image (JPG, JPEG, PNG)** and extract text using OCR  
✔️ **Convert extracted text to speech** in the detected language  
✔️ **Translate the extracted text** into multiple languages  
✔️ **Convert translated text into speech**  
✔️ **Download the original or translated speech as an audio file**  
✔️ **User-friendly web interface** for smooth interaction  

---

## 🛠️ Technologies Used  

| Technology  | Description |
|------------|-------------|
| **Flask** | Python framework for building the web application |
| **Tesseract OCR** | Optical Character Recognition engine for text extraction |
| **gTTS (Google Text-to-Speech)** | Converts text into speech audio |
| **OpenCV** | Image processing library for handling images |
| **Google Translate (Python Library)** | Translates text into multiple languages |
| **Bootstrap, HTML, CSS** | Frontend for user interaction |

---

## 🛠️ Installation Guide  

For **detailed installation steps**, refer to the **[User Manual & Installation Guide](INSERT_LINK_HERE)**.  

---

## 🎯 How to Use  

### **Step 1: Upload an Image**  
- Click **"Upload Image"**  
- Select a **JPG, JPEG, or PNG** file  
- The system processes the image and extracts text  

### **Step 2: Listen to Extracted Text**  
- Once processed, the **extracted text is displayed**  
- The text is automatically **read aloud using TTS**  

### **Step 3: Translate the Extracted Text (Optional)**  
- Select a **target language** from the dropdown list  
- Click **"Translate"**  
- The translated text will be displayed  

### **Step 4: Listen to Translated Speech**  
- The **translated text is also converted into speech**  
- The system will automatically **play the translated audio**  

### **Step 5: Download the Audio**  
- Click the **Download button** to save either the **original or translated speech file**  
- The file is saved in **MP3 format**  

---

## 🛠️ Troubleshooting  

💡 **Having trouble? Try these quick tips!**  

- 🔹 **Image not uploading?** → Make sure it's a **JPG, JPEG, or PNG** file.  
- 🔹 **Text not detected?** → Use a **clear, high-quality image** with readable text.  
- 🔹 **OCR result not accurate?** → Printed text works best. Try improving **contrast and brightness**.  
- 🔹 **Translation not showing?** → Double-check the **selected language** and retry.  
- 🔹 **No sound?** → Turn up the **volume** and check browser **audio settings**.  
- 🔹 **Audio file not playing?** → Ensure it’s a **.mp3 file** and try another media player.  
- 🔹 **App not running?** → Install dependencies with `pip install -r requirements.txt` and restart.  

✨ **Still need help?** Check out the full documentation [here](https://github.com/ninismr/FlaskWebApp_ImageToSpeechConverter).  

---

## 🌍 Supported Languages  

The application supports **multiple languages** for both **text extraction and speech conversion**. Some supported languages include:  

- **English** 🇬🇧  
- **Spanish** 🇪🇸  
- **French** 🇫🇷  
- **German** 🇩🇪  
- **Chinese** 🇨🇳  
- **Japanese** 🇯🇵  
- **Arabic** 🇸🇦  
- **Indonesian** 🇮🇩  
- **Hindi** 🇮🇳  
- ...and more!  

_(Exact supported languages depend on the OCR and TTS configurations in the system.)_  

---










Sure! Here’s a more detailed **introduction** for your **README.md**, making it even more engaging and informative:  

---

# 🗣️ I.HEAR.YOU - Image to Speech Converter  

**A Flask Web Application for Extracting, Translating, and Converting Image Text into Speech**  

---

## 📌 Introduction  

In today's digital world, **text is everywhere**, from books and signs to online articles. However, **not everyone can easily access or understand written content**—whether due to visual impairment, language barriers, or reading difficulties. **I.HEAR.YOU** is a **Flask-based web application** designed to **bridge this gap by extracting text from images, translating it into different languages, and converting it into natural-sounding speech**.  

This project combines **Optical Character Recognition (OCR)** with **Text-to-Speech (TTS) technology**, allowing users to:  
✅ **Extract text** from an image with **high accuracy**  
✅ **Listen to the extracted text** in a human-like voice  
✅ **Translate the text** into multiple languages  
✅ **Hear and download the translated speech**  

Whether you need to **read a foreign sign, assist someone with a visual impairment, or simply want to listen to text instead of reading**, this application offers an **efficient and accessible** solution. Built with **Flask, Tesseract OCR, gTTS, and OpenCV**, it delivers a **lightweight yet powerful tool** for real-world use.  

---

## 🌟 Features  

✔️ **Upload an image (JPG, JPEG, PNG)** and extract text using OCR  
✔️ **Convert extracted text to speech** in the detected language  
✔️ **Translate the extracted text** into multiple languages  
✔️ **Convert translated text into speech**  
✔️ **Download the original or translated speech as an audio file**  
✔️ **User-friendly web interface** for smooth interaction  
✔️ **Lightweight and fast processing**  

---

### 🔥 What’s Improved in This README?  
✔️ **Expanded introduction with real-world applications**  
✔️ **Stronger focus on accessibility and practical uses**  
✔️ **More engaging and easy to understand**  

Now your **README introduction** is more engaging, informative, and explains **why** your project is useful. Let me know if you'd like more refinements! 🚀🔥
