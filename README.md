# Medical Information RAG Assistant

## Project type
Browser-based educational RAG demonstration.

## Files
- `index.html` — application interface
- `documents/` — four separate medical knowledge-base documents
- `README.md` — setup and running instructions

## Run in VS Code
1. Install Visual Studio Code.
2. Extract this ZIP.
3. Open VS Code.
4. Select **File > Open Folder**.
5. Choose the extracted `Medical_RAG_VSCode_Project` folder.
6. Install the **Live Server** extension by Ritwick Dey.
7. Right-click `index.html`.
8. Select **Open with Live Server**.
9. The application opens in your browser.

## Test questions
- What are common symptoms of diabetes?
- What are common causes of fever?
- How does the common cold spread?
- What are healthy lifestyle habits?
- What is quantum computing? (tests out-of-knowledge-base handling)

## Important limitation
This version is a local browser demonstration using keyword-based retrieval. It does not call the Gemini API and does not diagnose patients or recommend personalized treatment. For a production Gemini RAG system, use a secure backend and verified medical sources.
