# Social Media Content Analyzer

## Overview
Social Media Content Analyzer is a web application that allows users to analyze social media content from uploaded PDFs and image files. The app extracts text using advanced parsing and OCR techniques, evaluates engagement scores, and provides actionable suggestions to improve content visibility and interaction.

## 🚀 Features

1. **Document Upload**:
   - Users can upload PDFs or image files.
   - Drag-and-drop or file picker interface.

2. **Text Extraction**:
   - Extracts text from PDFs using `pdf.js`.
   - Applies OCR to images with `tesseract.js`.

3. **Content Analysis**:
   - Calculates engagement scores based on hashtags, mentions, emojis, and word count.
   - Suggests improvements such as adding hashtags, questions, or emojis to enhance engagement.
    
4. **Error Handling**
   - Ensures proper error feedback for unsupported file types and failed text extractions.
   
5. **Loading State**
   - Displays a loading spinner (Loader from lucide-react) while processing files.

6. **User Interface**:
   - Dark/Light mode toggle
   - Intuitive interface for uploading files and viewing results.
   - Displays extracted text and analysis in a user-friendly format.
  
## 🚀 Live Link
https://anshul-parihar.github.io/Social-Media-Content-Analyzer/

## 🛠️ Technologies Used
- **Frontend**: React.js
- **OCR**: Tesseract.js
- **PDF Parsing**: PDF.js

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Anshul-Parihar/Social-Media-Content-Analyzer.git

   cd Social-Media-Content-Analyzer
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```
   Runs the app in the development mode.
   Open http://localhost:3000 to view it in your browser.
   The page will reload when you make changes.
   
## 📁 Project Structure
    src/
    ├── components/
    │   └── FileUploader/
    │       ├── FileUploader.css
    │       └── FileUploader.jsx
    ├── utils/
    │   └── textExtraction.js
    └── App.css
    └── App.jsx
    └── index.jsx

## 📸 Project Screenshots
![Screenshot 2025-01-20 040000](https://github.com/user-attachments/assets/239dd8ef-169c-4e4f-9ff6-a3e5c0cae3d5)
![Screenshot 2025-01-20 035724](https://github.com/user-attachments/assets/c963a6e2-77f1-4bb9-9f2d-469d00db3a06)

## Brief Write-Up of Approach

The Social Media Content Analyzer was designed to make analyzing and improving social media posts intuitive and efficient. Users upload files via drag-and-drop or file picker, ensuring a seamless experience. For text extraction, PDF files are parsed using `pdf.js`, leveraging its structured text capabilities. Images are processed through `tesseract.js`, enabling accurate OCR-based text recognition. Extracted text is then evaluated for engagement factors such as hashtags, mentions, emojis, word count, and questions. These metrics determine an overall engagement score. Based on the analysis, actionable suggestions like adding hashtags or emojis are provided to optimize the content's reach and interaction potential.

The application ensures robustness by handling diverse file types and providing detailed feedback. A visually engaging interface enhances usability, while modular components ensure scalability and maintainability.

## Future Enhancements

To make the project more robust and user-friendly, consider:

**UI Improvements:**
Add a progress bar for file processing.
Enhance drag-and-drop with visual feedback.

**Localization:**
Support OCR for multiple languages in Tesseract.js.

**Backend Support:**
Offload text extraction and analysis to a backend service for heavy files.

**User Data Persistence:**
Save analysis history using local storage or a backend database.


## Contact

If you want to contact me, you can reach me through below handles.

[![linkedin](https://img.shields.io/badge/Anshul_Parihar-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anshul-parihar-8251a4206/)
[![GitHub](https://img.shields.io/badge/Anshul_Parihar-20232A?style=for-the-badge&logo=Github&logoColor=white)](https://github.com/Anshul-Parihar)

© 2025 Anshul Parihar



## Show your support

Give a ⭐️ if you like this project!

