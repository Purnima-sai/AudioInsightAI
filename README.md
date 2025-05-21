# 🎧 AudioInsightAI

AudioInsightAI is a smart audio analysis toolkit that allows users to upload any audio file and gain meaningful insights from it through transcription, summarization, question-answering, sentiment analysis, and feedback evaluation.

---

## 🚀 Features

- ✅ **Transcription** — Convert speech from audio into clean text using Whisper.
- ✅ **Summarization** — Summarize long transcripts into short, readable summaries.
- ✅ **Question Answering** — Ask any question from the transcribed content.
- ✅ **Sentiment Analysis** — Analyze the tone (positive/negative/neutral) of the transcript or user feedback.
- ✅ **Feedback Processing** — Let users type feedback and get a smart emotional response.
- ✅ **Interactive CLI** — User-friendly command-line interface to explore all features easily.

---

## 🛠️ Tech Stack

- [Whisper](https://github.com/openai/whisper) – For accurate audio transcription.
- [Transformers (HuggingFace)](https://huggingface.co/transformers/) – For summarization, QA, sentiment analysis.
- Python, Torch, OpenAI Whisper, Google Colab-compatible.

---

## 📦 Installation

Make sure you’re using **Google Colab** or a Python 3.7+ environment with internet access.

Install dependencies:

```bash
!pip install openai-whisper
!pip install transformers
!pip install torchaudio
