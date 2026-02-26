# DocuMind


DocuMind is a privacy-focused, single-file web application designed to turn your static HTML archives into an interactive, AI-powered knowledge base. By leveraging IndexedDB for local storage and the Gemini 2.5 Flash API for intelligence, DocuMind allows you to read and chat with your documents without ever uploading them to a central server.

<img width="1109" height="611" alt="screenshot" src="https://github.com/user-attachments/assets/d90caa30-27f5-426d-9c51-b40abf0c88d9" />

<br/><br/>
✨ Features

Local Persistence: All HTML files and chat histories are stored directly in your browser's IndexedDB. No backend required.

AI Document Analysis: Integrated chat window powered by Gemini 2.5 Flash to ask questions, summarize content, or find specific details within the current page.

Context-Aware Chat: Automatically feeds the document content to the AI, maintaining context-specific conversation threads for every file in your library.

Clean Reading UI: Collapsible sidebar for document navigation, Markdown-rendered AI responses, and an isolated iframe reader.

Privacy First: Your Gemini API key is stored in localStorage, and all document processing happens between your browser and the API endpoint.

Zero Dependencies: A single HTML file that just works. (Uses Tailwind CSS and Marked.js via CDN).
<br/><br/>

🚀 Getting Started

Download: Save the index.html file to your computer.

Open: Double-click index.html to open it in any modern web browser.

Configure: Click the Settings (gear icon) and enter your Google Gemini API Key.

Import: Click Add HTML Files to populate your sidebar with your local documentation.

Read & Chat: Select a file from the sidebar to view it and start a conversation with the AI.

🛠️ Built With

Tailwind CSS: For the modern, responsive interface.

Marked.js: To render beautiful Markdown responses from the AI.

IndexedDB: For high-performance local data storage.

Gemini 2.5 Flash: For fast and accurate document reasoning.


🔒 Privacy & Security

DocuMind is designed with data sovereignty in mind:

No Tracking: There are no analytics or third-party trackers.

Direct Storage: Your documents stay in your browser profile.

Easy Wipe: Use the "Clear All Data" button in settings to instantly delete all local databases and saved keys.

📝 License

This project is open-source. Feel free to modify and distribute it as you see fit.
