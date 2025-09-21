# VIOLA: Video Integration of Object Detection, Language Insights, and Accessibility  

### 🎯 Overview  
**VIOLA** is a real-time video analysis framework that integrates **YOLOv8** (object detection), **Whisper/Google STT** (speech-to-text), and **GPT-4** (contextual insights) into a unified pipeline. The system enhances **accessibility, comprehension, and situational awareness** for live video streams by combining vision, audio, and language-based intelligence.  

---

### 🛠️ Tech Stack  
- **Object Detection** → YOLOv8  
- **Speech-to-Text** → OpenAI Whisper, Google Speech-to-Text  
- **Text-to-Speech** → Pyttsx3  
- **Language Insights** → GPT-4  
- **Interface** → Custom user-friendly UI for live visualization  

---

### 📌 Key Features  
- Real-time **object detection** with YOLOv8.  
- **Speech transcription** via Whisper/Google STT.  
- **Contextual analysis & insights** with GPT-4.  
- **Accessibility focus** with text-to-speech and enriched video overlays.  
- Modular design for **surveillance, education, assistive tech, and immersive UX**.  

---

### 🔬 Methodology  
1. **Capture live video** (camera/webcam).  
2. **YOLOv8 detects objects** within frames.  
3. **Whisper/Google STT transcribes speech** in real time.  
4. **GPT-4 generates contextual insights** (summaries, sentiment, entity recognition).  
5. **User interface overlays** objects, transcripts, and insights on live video.  

---

### 📊 Results  
- Accurate **real-time detection** of objects and speech transcription.  
- Successful **fusion of multi-modal insights** into a single visual display.  
- Demonstrated potential in **accessibility applications** (live captioning, assistive video tools).  

---

### 🚀 Future Work  
- Multimodal fusion (video + audio + text at deeper levels).  
- Continual learning for long-term adaptability.  
- Edge optimization for mobile/IoT deployment.  
- Privacy-preserving and federated learning approaches.  

---

### 🏆 Recognition  
- Published as *“VIOLA: Video Integration of Object Detection, Language Insights and Accessibility”* in the 2024 International Student Conference.  
- Received awards for **Best AI for Social Impact**.  

---

### ⚡ Quick Start  

#### 1. Clone the repository  
git clone https://github.com/yourusername/viola.git  
cd viola  

#### 2. Create a virtual environment (recommended)  
python -m venv venv  
source venv/bin/activate   # On Linux/Mac  
venv\Scripts\activate      # On Windows  

#### 3. Install dependencies  
pip install -r requirements.txt  

#### 4. Run the application  
python main.py  

#### 5. Expected workflow  
- A window will open showing live **video feed**.  
- Objects will be detected and highlighted via **YOLOv8**.  
- Speech will be transcribed in **real time** using Whisper/Google STT.  
- **GPT-4 insights** will be generated and displayed alongside the video.  
- Optionally, **TTS (pyttsx3)** will read insights aloud for accessibility.  

---

### 📂 Repository Structure  
├── /src  
│   ├── object_detection/      # YOLOv8 implementation  
│   ├── speech_to_text/        # Whisper + Google STT  
│   ├── text_to_speech/        # Pyttsx3 module  
│   ├── insights/              # GPT-4 contextual analysis  
│   └── ui/                    # User interface  
├── /data                      # Sample test data  
├── main.py                    # Entry point  
├── requirements.txt           # Dependencies  
└── README.md                  # Documentation  

---

### 🤝 Contributors  
- **Ram Kasuru** – Computer Science (AI & ML), Dayananda Sagar University  
- Jeramiah T Varghese, C S Jeevan, Hridanshu Ruparel  
