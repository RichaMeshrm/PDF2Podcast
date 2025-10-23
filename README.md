Transform any PDF document into an engaging audio podcast using Google Gemini’s Generative AI and Text-to-Speech (TTS) models — all through a simple Gradio web interface.

🚀 Features

✅ Upload any PDF file
✅ Automatic text extraction with LangChain PyPDFLoader
✅ Smart summarization using Gemini 2.5 Flash
✅ Realistic AI voice narration via Gemini’s TTS (gemini-2.5-flash-preview-tts)
✅ Interactive Gradio UI for easy use
✅ Output saved as .wav audio file

🧩 Tech Stack
Component	Purpose
Python	Core programming language
Gradio	For creating a clean and interactive UI
LangChain Community	To handle PDF document loading (PyPDFLoader)
Google Generative AI SDK (genai)	For content generation and TTS
wave module	To save generated audio
pypdf	To support PDF reading operations

🧰 How It Works
Step-by-Step Flow:

Upload PDF
→ The file is processed using PyPDFLoader from LangChain.

Extract Text
→ Each page’s text content is extracted and concatenated.

Summarization (Gemini 2.5 Flash)
→ The model extracts meaningful insights using a natural language prompt.

Audio Generation (Gemini TTS)
→ The summarized text is converted to speech using gemini-2.5-flash-preview-tts.

Output
→ The audio is saved as output.wav and played directly in Gradio.
