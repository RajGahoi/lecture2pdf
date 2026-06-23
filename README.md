# 🎓 Lecture2PDF AI

<div align="center">

### Convert Lecture Videos into Clean, Study-Ready PDFs Automatically

Stop wasting hours taking screenshots during lectures. Let Lecture2PDF AI detect slides, extract key frames, and generate organized PDFs in minutes.

🚀 Fast • 🔒 Private • 📚 Student Friendly

</div>

---

## 📖 Overview

Lecture2PDF AI is a Chrome Extension that automatically extracts presentation slides from lecture videos and converts them into a downloadable PDF.

Whether you're studying from YouTube, Udemy, Coursera, or recorded college lectures, Lecture2PDF AI helps you focus on learning instead of manually capturing screenshots.

---

## ❌ The Problem

Imagine watching a 2-hour lecture.

Every time the slide changes, you:

* Pause the video
* Take a screenshot
* Save it
* Resume watching

After the lecture, you end up with:

* Hundreds of screenshots
* Duplicate images
* Disorganized notes
* Hours wasted

Most students spend more time collecting notes than actually studying.

---

## ✅ The Solution

Lecture2PDF AI automates the entire process.

Simply:

1. Open a lecture video
2. Click **Scan Video**
3. Review detected slides
4. Generate PDF

That's it.

The extension handles everything automatically.

---

## ✨ Features

### 🔍 Smart Slide Detection

Automatically identifies meaningful slide transitions throughout the lecture.

---

### 🧠 Adaptive Thresholding

Uses Otsu's Thresholding Algorithm to dynamically determine the best detection threshold for each video.

---

### 📸 Duplicate Reduction

Filters unnecessary captures and focuses on important slide changes.

---

### 🖼 Slide Review Dashboard

Preview all detected slides before generating the final PDF.

You can:

* Review captures
* Remove unwanted slides
* Fine-tune results

---

### 📄 PDF Generation

Convert selected slides into a professional PDF instantly.

Perfect for:

* Exam preparation
* Revision notes
* Quick review sessions

---

### 🔒 Privacy First

Everything runs locally in your browser.

No:

* Cloud uploads
* External servers
* Data collection
* Tracking

Your lecture data never leaves your device.

---

# 🚀 How It Works

```text
Open Lecture Video
        ↓
Scan Video
        ↓
Detect Slide Changes
        ↓
Review Captured Slides
        ↓
Generate PDF
        ↓
Download Notes
```

---

## ⚙️ Technology Stack

| Technology         | Purpose                |
| ------------------ | ---------------------- |
| JavaScript         | Core Application Logic |
| Chrome Manifest V3 | Extension Framework    |
| HTML/CSS           | User Interface         |
| Canvas API         | Frame Processing       |
| PDF-Lib            | PDF Generation         |
| Otsu's Method      | Threshold Optimization |
| Service Workers    | Background Processing  |

---

## 🧠 Detection Algorithm

### Frame Analysis

Lecture2PDF samples frames across the lecture timeline and converts them into lightweight brightness grids.

This significantly reduces processing cost while maintaining accuracy.

---

### Change Detection

Consecutive frames are compared to calculate visual differences.

The algorithm ignores:

* Mouse movements
* Cursor activity
* Minor animations

while detecting actual slide transitions.

---

### Adaptive Threshold Selection

Instead of relying on a fixed threshold, Otsu's Method automatically calculates the optimal threshold for every lecture.

Benefits:

* Higher accuracy
* Fewer duplicates
* Better results across different video styles

---

# 📦 Installation

## Method 1: Install from Source

### 1. Clone the Repository

```bash
git clone https://github.com/RajGahoi/lecture2pdf.git

cd lecture2pdf
```

Or download the ZIP file and extract it.

---

### 2. Open Chrome Extensions

Open Chrome and visit:

```text
chrome://extensions/
```

---

### 3. Enable Developer Mode

Turn ON **Developer Mode** from the top-right corner.

---

### 4. Load the Extension

Click:

```text
Load Unpacked
```

Select the project folder containing:

```text
manifest.json
```

---

### 5. Pin the Extension

Click the Extensions icon and pin:

```text
Lecture2PDF AI
```

The extension is now ready to use.

---

# 📚 Usage

### Step 1

Open any lecture video.

Supported platforms include:

* YouTube
* Coursera
* Udemy
* Khan Academy
* PhysicsWallah
* Unacademy
* Most HTML5 video players

---

### Step 2

Click the Lecture2PDF AI extension icon.

---

### Step 3

Press:

```text
🔍 Scan Video
```

The extension will automatically analyze the lecture.

---

### Step 4

Review the detected slides.

Remove any unwanted captures if necessary.

---

### Step 5

Click:

```text
⚡ Generate PDF
```

The PDF will be generated and downloaded automatically.

---

# 🎯 Use Cases

### 👨‍🎓 Students

Create revision notes instantly.

### 👩‍🏫 Teachers

Generate lecture handouts from recorded sessions.

### 📚 Online Learners

Capture key slides from online courses.

### 🎓 Exam Preparation

Build concise study material quickly.

---

# 🔮 Future Roadmap

* AI-powered lecture summarization
* OCR text extraction
* Export to Markdown
* Export to Notion
* Multi-language support
* Smart chapter detection
* Lecture transcript integration
* Cloud synchronization

---

# 🤝 Contributing

Contributions are welcome.

If you'd like to improve the project:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

# ⭐ Support

If Lecture2PDF AI saved you time, please consider giving this repository a star.

It helps more students discover the project and motivates future development.

---

<div align="center">

### Built for Students ❤️

Transform lectures into organized study material — automatically.

⭐ Star the project if you found it useful.

</div>
