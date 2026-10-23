# UPSC Interview Voice Practice — GitHub Pages build

This is the static, GitHub Pages-compatible build. It includes 5 judge personas, 25 practice questions, 20-minute timer, browser text-to-speech for spoken questions, speech-to-text answer capture, typed-answer fallback, and a downloadable local practice report.

## Publish on GitHub Pages from Android
1. Download and extract this ZIP.
2. In your GitHub repository, upload `index.html`, `app.js`, and `README.md` to the repository root (not inside another folder).
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, choose your branch (usually `main`) and folder `/ (root)`, then Save.
5. Open the resulting `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/` link in **Google Chrome** on Android.
6. When prompted, allow microphone access. If you previously blocked it: Chrome → site info/permissions → Microphone → Allow, then reload.
7. Tap **Test voice** before starting. Tap **Start speaking** to record an answer and **Stop speaking** when done.

## Important voice limitations
- This is browser voice, not a separate AI voice engine. Text-to-speech voices come from Android/Chrome's available voices. Set them up in Android Settings → General management → Text-to-speech output.
- Speech recognition depends on Chrome, internet connection, language availability, and microphone permission. English (`en-IN`) is the most reliable choice to test first; Hindi/Marathi availability varies by device/service.
- Use the HTTPS GitHub Pages website, not a local file preview or GitHub's code editor preview.
- GitHub Pages only hosts static files. AI-generated questions and AI-quality evaluation require a separate backend service; this build uses built-in questions and a local completion report without exposing an API key in browser code.
