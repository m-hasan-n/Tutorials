# 🎥🧠 Multimodal Video Summarization with LLMs

This project demonstrates a simple but powerful **multimodal AI pipeline** that integrates **vision, audio, and language** using state-of-the-art models like **Whisper**, **BLIP**, and **Phi-2**.

🔗 **Try it in Google Colab**:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/yourrepo/blob/main/your_notebook.ipynb)

---

## 🧠 Project Overview

Given a short video clip, the system performs the following steps:

1. 🎞️ Extracts keyframes from the video
2. 🎧 Separates and transcribes the audio using **Whisper**
3. 🖼️ Captions video frames using a **vision-language model** (BLIP)
4. 🤖 Uses **Phi-2** to reason over both image captions and audio transcript to produce a coherent, human-readable **video summary**

---

## 🧪 Technologies Used

| Component        | Model / Tool            |
|------------------|--------------------------|
| Audio Transcription | OpenAI Whisper (`transformers`) |
| Image Captioning | BLIP (Hugging Face) |
| Language Understanding | Phi-2 (Microsoft) |
| Notebook Runtime | Google Colab (Python) |

---

## 📌 Example Output

**Video Scene**: A surgeon performing a laparoscopic procedure.

**Whisper Transcription**:
> “We’re beginning the procedure. The patient is stable and under anesthesia.”

**BLIP Image Captions**:
- "Surgeon preparing tools in an operating room"
- "Medical staff gathered around the patient"

**Final Summary (GPT-4)**:
> “This video depicts a surgical team performing a laparoscopic procedure. The patient is stable, and the staff are preparing and coordinating under surgical lighting.”

---

## 📚 Related Blog Post

📖 Read the full write-up on Medium:  
👉 [Seeing and Hearing Like AI: A Multimodal LLM Pipeline for Video Understanding](https://medium.com/@yourusername/multimodal-ai-video-summary)

---

## 🤝 Contact

If you're interested in **multimodal AI**, **LLMs**, or applied computer vision + NLP projects, feel free to connect!

🌐 [yourwebsite.com]  
💼 [LinkedIn](https://linkedin.com/in/yourprofile)

---

## 📄 License

MIT License – feel free to use, fork, and build upon this work.
