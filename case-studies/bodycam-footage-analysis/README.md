# 🎥 Metadata Extraction from Bodycam Footage

## 🎯 Objective

Analyze a bodycam video capturing a paranormal event to extract hidden metadata and uncover a hidden string.

This challenge comes from the hacktoria.com

---

## 🎥 Source Material

A video file recorded from a police officer’s body-worn camera, depicting an alleged ghost sighting.  
The task was to investigate the file for any hidden or embedded information beyond its visible content.

---

## 🛠 Methodology

1. **Metadata Extraction**

   - Uploaded the video file to [Metadata2Go.com](https://www.metadata2go.com/) for online metadata analysis
   - Analyzed all available fields, including technical details, timestamps, and embedded comments

2. **Hidden Data Identification**
   - Discovered a string hidden in the **Comment** metadata field
   - No evidence of hidden information in the video frames or audio track (lack of an audio); critical data was solely stored in the metadata

---

## 📌 Results

- **Hidden String Found:**  
  Example: `fh453n3fk45b384gm$&%#fjksdfmo94853ff`

- **Location of the Data:**
  - Metadata Field: `Comment`
  - Extraction Method: Online metadata analyzer (Metadata2Go)

**Video:**

- ![boodycam_footage](./bodycam-officer-1.mp4)

---

## 🧠 Findings

- Digital files may contain crucial hidden information beyond visible content.
- **Metadata fields** such as `Comment`, `Description` are common hiding places for embedded strings, flags, or forensic artifacts.
- Regular metadata analysis should be a **standard step** in any digital forensic or OSINT investigation, especially when dealing with video, image, or document files.
- **Metadata2Go** proved effective for quick online metadata extraction without the need for command-line tools.

---

## 🔗 Related Links

- [Metadata2Go – Free Online Metadata Viewer](https://www.metadata2go.com/)
