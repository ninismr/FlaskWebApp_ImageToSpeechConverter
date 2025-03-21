<p align="center">
  <img src="ihearyou.png" alt="I.HEAR.YOU Logo" width="200">
</p>

<p align="center">
  <strong>A Web-Based Image-To-Speech Converter Application</strong><br>
  <em>Extracting and Converting Image Text into Speech Using Optical Character Recognition and Speech Synthesis with Translation Support</em>
</p>

<p align="center">
  🔹 Built with <strong>Flask</strong>, <strong>Tesseract OCR</strong>, <strong>gTTS</strong>, <strong>googletrans</strong>, and <strong>OpenCV</strong> 🔹
</p>

---

## 📌 Introduction  

In today's digital world, **text is everywhere**, from books and signs to online articles. However, **not everyone can easily access or understand written content**—whether due to visual impairment, language barriers, or reading difficulties. **I.HEAR.YOU** is a **Flask-based web application** designed to **bridge this gap by extracting text from images, translating it into different languages, and converting it into natural-sounding speech**.  

This project combines **Optical Character Recognition (OCR)** with **Text-to-Speech (TTS) technology**, allowing users to:  
✅ **Extract text** from an image containing text  
✅ **Listen** to the extracted text in a **human-like voice**  
✅ **Translate the text** into multiple languages  
✅ **Hear and download** the translated speech  

Whether you need to **read a foreign sign, assist someone with a visual impairment, or simply want to listen to text instead of reading**, this application offers an **efficient and accessible** solution. Built with **Flask, Tesseract OCR, gTTS, googletrans, and OpenCV**, it delivers a **lightweight yet powerful tool** for real-world use.    

### 🔍 **How It Works:**  
1️⃣ **Users upload an image** (JPG, JPEG, PNG) containing text  
2️⃣ **The system extracts the text** from the image using **Tesseract OCR**  
3️⃣ **The extracted text is converted into speech** in a **human-like voice** using **gTTS (Google Text-to-Speech)**  
4️⃣ **Users can translate the extracted text** into another language  
5️⃣ **The translated text is also converted into speech**, played with the **correct accent**, and can be **downloaded as an audio file**  

  
### 🎯 **This Application is Useful For:**  
👉 **Visually impaired users** who need text read aloud  
👉 **Multilingual users** who want to translate text and hear it in another language  
👉 **Language learners** who want to hear text in different languages and practice pronunciation  
👉 **Digital content consumers** who prefer listening over reading  

---

## 🌟 Features  

✔️ **Upload an image** (JPG, JPEG, PNG) and extract text using OCR  
✔️ **Convert extracted text to speech** in the detected language  
✔️ **Translate the extracted text** into multiple languages  
✔️ **Convert translated text into speech**  
✔️ **Autoplay text-to-speech audio** after processing  
✔️ **Download the translated speech** as an audio file for offline use  
✔️ **Supports multiple languages** for both text recognition and speech output  
✔️ **User-friendly and lightweight web interface** for smooth interaction and fast processing  

---

## ⚙️ Technologies Used  

| Technology  | Description |
|------------|-------------|
| **Flask** | Python framework for building the web application |
| **Tesseract OCR** | Optical Character Recognition engine for text extraction |
| **gTTS (Google Text-to-Speech)** | Converts text into speech audio |
| **OpenCV** | Image processing library for handling images |
| **Google Translate (Python Library)** | Translates text into multiple languages |
| **Bootstrap, HTML, CSS** | Frontend for user interaction |

---

## 🪄 Installation Guide  

For installation instructions, refer to the **[Installation Guide](https://github.com/ninismr/FlaskWebApp_ImageToSpeechConverter/blob/main/USER%20MANUAL%20AND%20INSTALLER%20GUIDE_Mulya%20Fajar%20Ningsih%20Alwi_001202000101.pdf)** provided in the repository.  

---

## 🧐 How to Use  

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
- Click the **Download button** to save the **translated speech file**  
- The file is **saved in audio format** for **offline use** 

---

## 🎥 Application Demo  

<p align="center">
  📌 <strong>Curious to see how I.HEAR.YOU works? Watch the demo video by clicking the image below!</strong><br><br>
  <a href="https://drive.google.com/file/d/1C7sB-fylm3l1kzu4WGZgoPv-IDjBU5ys/view?usp=sharing">
    <img src="https://github.com/ninismr/FlaskWebApp_ImageToSpeechConverter/blob/main/thumbnail.png" alt="Watch the Demo Video" width="75%">
  </a>
</p>

<p align="center">
  ⚠️ <strong>If the video doesn't play, you can download it from Google Drive or from the video file provided in the repository.</strong>
</p>

--- 

### 🎬 **What’s in the Demo?**  
**This demo showcases the full functionality of I.HEAR.YOU, including:**  

1️⃣ **Exploring the About Page**  
   - A quick overview of the app’s purpose and features before jumping into action.  

2️⃣ **Uploading Images & Extracting Text**  
   - The homepage lets users **upload an image** with text for processing.
   - The demo tests the app’s OCR accuracy by **uploading five different images** under different conditions.

3️⃣ **OCR Accuracy Across Various Image Types**  
   - **Book Page (Korean text)** – Accurately extracts and reads aloud the **exact** text from a book page in Korean, then translates it into **Japanese** and autoplays the translated audio. ✅ 
   - **Handwritten (English Text)** – Successfully extracts handwritten text and auto-reads it, then translates it into **German** and autoplays the translated audio. ✅ 
   - **Low-Light Image (Arabic text)** – Accurately extracts Arabic text **even from a very dark image** and reads it aloud in Arabic, then translates it into **French** and autoplays the translated audio. ✅  
   - **Street Sign (English text)** – Successfully recognizes and extracts text from a **street sign**, then translates it to **Indonesian** and autoplays the translated audio. ✅  
   - **Newspaper Page (English structured layout text)** – Successfully recognizes both **left and right columns** and extracts text in the correct reading order. ✅

4️⃣ **Seamless Speech & Translation Features**  
   - **Auto-reads** both the original and translated text, so users don’t have to press play.  
   - **Maintains punctuation, capitalization, and structure** in the extracted text.  
   - Users can **download the translated speech** as an audio file for offline use.

5️⃣ **Conclusion**  
   - The **OCR performs accurately** across different image conditions (book pages, handwriting, low-light images, street signs, and newspaper layouts).  
   - **Text extraction maintains proper punctuation, uppercase/lowercase, and formatting.**  
   - **Speech playback is automatic**, making it highly accessible for visually impaired users.  
   - **Processing time increases with more complex images** (e.g., newspaper pages), but the app still extracts text correctly.  

### 🏆 **Why Should You Try This App?**  

   ✨ **See for yourself** how well the app extracts text from different types of images and handle the speech conversion!  
   ✨ **Experience automatic speech playback** that makes content accessible to everyone.  
   ✨ **Test its powerful OCR & translation capabilities** on your own images and see how it adapts across languages.  

💡 **Ready to try it?** Upload your own images and let I.HEAR.YOU do the work! 🚀  

---

## 🛠️ Troubleshooting  

💡 **Having trouble? Try these quick tips!**  

🔹 **Image not uploading?** → Make sure it's a **JPG, JPEG, or PNG** file.  
🔹 **Text not detected?** → Use a **clear, high-quality image** with readable text.  
🔹 **OCR result not accurate?** → Printed text works best. Try improving **contrast and brightness**.  
🔹 **Translation not showing?** → Double-check the **selected language** and retry.  
🔹 **No sound?** → Turn up the **volume** and check browser **audio settings**.  
🔹 **Audio file not playing?** → Ensure it’s an **audio file** and try another media player.  
🔹 **App not running?** → Install dependencies with `pip install -r requirements.txt` and restart.  

✨ **Still need help?** Check out the full troubleshoot documentation [here](https://github.com/ninismr/FlaskWebApp_ImageToSpeechConverter/blob/main/USER%20MANUAL%20AND%20INSTALLER%20GUIDE_Mulya%20Fajar%20Ningsih%20Alwi_001202000101.pdf).  

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

## 📖 Additional Documentation  

Learn more about:  
✅ **Application workflow** from image input to speech output  
✅ **Core technologies**: OCR, Speech Synthesis, NLP, and DSP  
✅ **System architecture and implementation**   

Refer to the **[Project Summary](https://github.com/ninismr/FlaskWebApp_ImageToSpeechConverter/blob/main/THESIS%20SUMMARY%20(EN)_Mulya%20Fajar%20Ningsih%20Alwi_001202000101.pdf)** and **[Slides](https://github.com/ninismr/FlaskWebApp_ImageToSpeechConverter/blob/main/PRESENTATION%20SLIDE_Mulya%20Fajar%20Ningsih%20Alwi_001202000101.pdf)** available in the repository.  

---



