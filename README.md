# 🌌 Aura AI
**Aura AI** is a modern, sleek, and fully static client-side AI chat interface designed to deliver a premium user experience with a dark liquid-glass theme (*glassmorphism*). 
Running entirely in the browser without any heavy server-side frameworks, it integrates advanced document parsing, image OCR, and a rich **Artifacts** panel for previewing code, diagrams, and interactive web pages.
---
## ✨ Key Features
* **💬 Modern Chat UI**: Sleek, animated, and minimalist chat window with an interactive conversation history sidebar.
* **📦 Artifacts System** (similar to Claude.ai):
  * Live rendering of AI-generated content (interactive HTML/CSS/JS in iframes, SVG drawings, markdown previews).
  * Dynamic rendering of schemas and charts using **Mermaid.js**.
  * Quick-action buttons to copy code snippets or download generated files.
* **📎 In-Browser File & Document Parsing**:
  * **PDFs**: In-browser text extraction (powered by `pdf.js`).
  * **Word Documents (.docx)**: Direct conversion and text extraction (powered by `mammoth.js`).
  * **Excel Sheets (.xlsx)**: Spreadsheet reading and rendering (powered by `SheetJS/xlsx`).
  * **Images & OCR**: Automatic text extraction from images and screenshots (powered by `tesseract.js`).
* **⚙️ Multi-Provider API Configuration**: Setup your custom API keys, endpoints, and model preferences directly in the settings modal (stored securely in browser `localStorage`).
* **🔌 Offline Fallback Simulation**: Offline sandbox mode that kicks in to mock AI responses for testing and UI evaluation when API keys are not provided.
---
## 🛠️ Built With
This project is built using vanilla technologies to guarantee fast loading speeds and zero build-step overhead:
* **HTML5** (Semantic structure)
* **Vanilla CSS** (Custom dark theme, CSS variables, glassmorphism blur effects, and smooth transitions)
* **Vanilla JavaScript** (Modular and reactive event-driven script)
* **Third-Party Libraries (Loaded via CDN)**:
  * [Marked.js](https://github.com/markedjs/marked) - Markdown rendering.
  * [PDF.js](https://mozilla.github.io/pdf.js/) - PDF document parsing.
  * [Mammoth.js](https://github.com/mvoloskov/mammoth.js) - Word document conversion.
  * [SheetJS (XLSX)](https://sheetjs.com/) - Spreadsheet handling.
  * [Tesseract.js](https://tesseract.projectnaptha.com/) - OCR (Optical Character Recognition).
  * [Mermaid.js](https://mermaid.js.org/) - Diagram and flowchart rendering.
---
## 🚀 Quick Start
Since this is a **static web application**, there are no installations, node packages, or build steps required!
1. Clone or download this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/aura-ai.git
   ```
2. Double-click the `index.html` file to open it directly in your web browser.
*💡 **Tip**: For the best development experience with auto-reload, you can use the **Live Server** extension in VS Code.*
---
## 📄 License
This project is licensed under the **MIT License**. You are free to use, modify, and distribute it, provided you include the original copyright notice and credit this project.
