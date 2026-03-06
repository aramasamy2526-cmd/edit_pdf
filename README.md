🎯 Why This Project?

Every day, job seekers, students, and working professionals need to add text to a PDF — filling out forms, adding signatures, updating resumes — and they get hit with a paywall.
Adobe Acrobat → ₹1,500/month
Smallpdf → ₹1,200/month
ilovepdf Pro → ₹800/month
This app is 100% free, runs on your own computer, and your files never leave your machine. 🔒

✨ Features
FeatureStatus📤 Upload any PDF✅ Done✏️ Click to add text anywhere on the page✅ Done🖱️ Drag & drop text to reposition✅ Done✏️ Double-click to edit existing text✅ Done🖊️ Highlight areas with color✅ Done🔄 Rotate pages✅ Done🔒 Password protect your PDF✅ Done💾 Download the final edited PDF✅ Done🗑️ Remove annotations✅ Done📝 Draw shapes & freehand🔜 Coming Soon🖼️ Insert images into PDF🔜 Coming Soon✍️ Digital signature support🔜 Coming Soon📋 Form filling🔜 Coming Soon

🖥️ Demo
Upload PDF → Click anywhere → Type your text → Download ✓

Screenshot / GIF coming soon!


🚀 Quick Start
1. Clone the repo
bashgit clone https://github.com/aramasamy2526-cmd/edit_pdf.git
cd edit_pdf
2. Create virtual environment
bashpython -m venv venv

# Windows
venv\Scripts\activate

# Mac / Linux
source venv/bin/activate
3. Install dependencies
bashpip install -r requirements.txt
4. Run the app
bashpython app.py
5. Open in browser
http://127.0.0.1:8000
That's it! 🎉

📁 Project Structure
edit_pdf/
├── app.py                  # FastAPI backend
├── requirements.txt        # Python dependencies
├── templates/
│   └── index.html          # Frontend UI
├── uploads/                # Temporary uploaded PDFs (auto-created)
├── outputs/                # Exported PDFs (auto-created)
└── README.md

🛠️ Tech Stack
LayerTechnologyBackendFastAPIPDF ProcessingpypdfPDF RenderingPDF.jsText OverlayReportLabFrontendHTML · CSS · Vanilla JavaScript

📖 How to Use
✏️ Adding Text

Upload your PDF using the upload zone
Make sure Text mode is selected (default)
Click anywhere on the PDF page — a text cursor appears
Type your text and press Enter
Your text is placed exactly where you clicked

🖱️ Moving Text

Switch to Select mode (↖ button in toolbar)
Click and drag any text to reposition it

✏️ Editing Text

Double-click any existing text to edit it inline

🖊️ Highlighting

Switch to Highlight mode
Click and drag over any area to highlight it
Choose your highlight color from the sidebar

💾 Downloading

Optionally set a password in the sidebar
Click Download PDF
Your edited PDF saves to your Downloads folder


⚙️ API Endpoints
MethodEndpointDescriptionPOST/uploadUpload a PDF filePOST/add_textAdd a text annotationPOST/add_highlightAdd a highlight boxPOST/update_annotationMove or edit an annotationPOST/remove_annotationDelete an annotationPOST/rotate_pageRotate a pagePOST/exportExport final PDFGET/get_annotationsGet all annotations
Full interactive API docs available at: http://127.0.0.1:8000/docs

🤝 Contributing
Contributions are welcome! If you want to add a feature or fix a bug:

Fork the repo
Create a new branch: git checkout -b feature/your-feature-name
Make your changes
Push and open a Pull Request


🔜 Roadmap

 Freehand drawing / pen tool
 Insert images into PDF pages
 Digital signature pad
 PDF form filling
 Multi-file merge (combine PDFs)
 Dark/light theme toggle
 Mobile-friendly UI


📜 License
This project is licensed under the MIT License — free to use, modify, and distribute.

👨‍💻 Author
Aravind Ramasamy
🔗 GitHub

⭐ Support
If this project helped you, please consider giving it a star ⭐
It helps others find this tool and motivates continued development!

💬 "Built for job seekers, students, and professionals who just need to edit a PDF — for free."
