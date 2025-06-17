# Flashcard Creator

A web-based tool to generate flashcards from educational material, with support for PDF ingestion, study mode, and export options (text and PDF).

## Features
- Upload PDFs to extract text or manually enter text.
- Generate Q&A flashcards using a simulated LLM process.
- Study mode for interactive learning.
- Export flashcards as text or PDF with a cover page.
- Clear input functionality to reset the app.

## How to Use
1. Open `index.html` in a browser.
2. Upload a PDF or enter text in the textarea.
3. Click "Generate Flashcards" to create flashcards.
4. Use Study Mode to review cards interactively.
5. Export flashcards as a text file or PDF.

## Tech Stack
- React (via CDN)
- Tailwind CSS (via CDN)
- jsPDF (for PDF export)
- pdf.js (for PDF ingestion)
- Google Fonts (Poppins)

## Notes
- This project uses CDNs for dependencies, so no build setup is required.
- PDF ingestion works with text-based PDFs (not scanned documents).
