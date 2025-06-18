# 🎥🧠 Multimodal Video Summarization with LLMs

This project demonstrates a simple but powerful **multimodal AI pipeline** that integrates **vision, audio, and language** using state-of-the-art models like **Whisper**, **BLIP**, and **Phi-2** LLMs.

🔗 **Try it in Google Colab**:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/m-hasan-n/Tutorials/blob/main/MultiModal/Video_Understanding.ipynb)

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

**Video Scene**: A man inflating a car tyre with a compressor and other tools.

**Whisper Transcription**:
> “If you've got a nail in your tyre, that's fine, but if the tyre's torn or the alloy wheel itself is damaged, you're going to need to call a breakdown service. You'll find you're a pair kit in ...”

**BLIP Image Captions**:
- 'a man kneeling down to a car with leaves on the ground',
- 'a man is fixing a car tire',
- 'a man changing the tire on a car'
- ...

**Final Summary (Phi-2)**:
> “A man is fixing a car tire with a sealant bottle and a compressor. He is also inflating the tire using the compressor. He suggests rolling the car forward to help the sealant spread around if the tire is not inflating properly...”

---

## 📚 Related Blog Post

📖 Read the full write-up on Medium:  
👉 [A Multimodal LLM Pipeline for Video Understanding](https://medium.com/@yourusername/multimodal-ai-video-summary)

---

## 🤝 Contact

If you're interested in **multimodal AI**, **LLMs**, or applied computer vision + NLP projects, feel free to connect!

🌐 [Meduim](https://medium.com/@eng-mhasan)  
💼 [LinkedIn](https://www.linkedin.com/in/drmhasan/)

---

## 📄 License

MIT License – feel free to use, fork, and build upon this work.
