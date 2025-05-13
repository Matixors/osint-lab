# 🗣️ Intercepted Audio Analysis – Spanish Communication

## 🎯 Objective

Analyze intercepted voice communication in Spanish to extract actionable intelligence using audio transcription and language processing tools.

This scenario comes from [limitless-osint](https://limitless-osint.com/)

---

## 🔊 Source Material

Multiple separate **audio recordings** presumed to capture a conversation between two Spanish-speaking individuals.  
Due to file size and storage limitations, the raw audio files are **not included in this repository**, but their content was analyzed in detail.

---

## 🛠 Methodology

1. **Metadata Inspection**

   - Used [metadata2go.com](https://metadata2go.com/) to check for timestamps, device info, GPS, or other EXIF data
   - Result: Metadata was either missing or inconclusive

2. **Audio Transcription**

   - Processed the audio files using **OpenAI’s Whisper AI** to obtain accurate Spanish-language transcripts
   - Output: Clean and timestamped transcriptions of both recordings

3. **Translation & Contextual Analysis**

   - Used **ChatGPT** to translate the transcriptions into English
   - Prompted the model to identify any:
     - Cultural or idiomatic nuances
     - References to locations, times, or specific technologies

4. **Information Extraction**
   - Identified key phrases and coded language
   - Inferred context and possible objectives or intentions from dialogue

---

## 📌 Results

**Language** Spanish  
**Transcript Quality** Clear enough for Whisper AI to produce highly accurate text  
**Key Findings** Identified coded language suggesting a plan of action  
**Contextual Insight** Technical and deliberate conversation indicating prior coordination  
**Cultural Notes** Use of informal terms specific to Latin American Spanish dialects such as 'CDMX'

---

## 🔍 Key Insight Example (Translated)

> "Este método de comunicación es mucho más seguro que nuestro protocolo habitual.”

**Translation:** This method of communication is much more secure than our usual protocol.”  
This implies a **pre-arranged meeting** and **the use of a more secure** communication method.

---

## 🔗 Related Links

- [Whisper AI](https://github.com/openai/whisper)
- [ChatGPT](https://chatgpt.com/)

