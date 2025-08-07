# 📊 AI Board Meeting Slide Generator

Automatically turn financial reports (PDF, Excel, CSV) into **executive-ready slides** powered by AI. Get GPT-generated summaries, visualized metrics, and downloadable presentations — all in one platform.

> ⚡ Built in 3 hours during the AI Hiring Show.

---

## 🚀 Live Demo

Coming Soon...

---

## 🎯 Features

- 📂 **Upload PDFs/Excels** with financial data
- 🧠 **AI Executive Summary** using GPT
- 📈 **Auto Visualizations** with Chart.js
- 🎞️ **Slide Generator** using Reveal.js
- 📤 **Export Slides as PDF**
- 💬 Simple, clean UI with Tailwind CSS

---

## 🖥️ Screenshots

> _Add screenshots after the build to show the UI!_

| Upload Page | Dashboard | Slide Viewer |
|-------------|-----------|---------------|
| ![upload](./screenshots/upload.png) | ![dashboard](./screenshots/dashboard.png) | ![slides](./screenshots/slides.png) |

---

## 🧱 Tech Stack

| Layer     | Tools Used                                |
|-----------|--------------------------------------------|
| Frontend  | React.js, Tailwind CSS, Reveal.js, Chart.js |
| Backend   | FastAPI, Pandas, PyPDF2, OpenAI GPT         |
| AI Engine | OpenAI GPT-4 API                           |
| Charts    | Chart.js                                   |
| File Parsing | `openpyxl`, `pandas`, `PyPDF2`         |

---

## 📁 Folder Structure (Frontend)

```bash
src/
├── components/
│   ├── UploadForm.jsx
│   ├── Dashboard.jsx
│   ├── SlideViewer.jsx
│   ├── SummarySection.jsx
│   └── Charts.jsx
├── services/
│   └── api.js
├── App.jsx
├── index.js
