# 🤖 Chatbot with Google Generative AI (Gemini) and File Uploads

This project features a chatbot that utilizes the Google Generative AI (Gemini) model via the Google API to provide intelligent responses to user queries. Users can also upload optional files (.pdf, .txt, .csv) for enhanced query processing. The bot's interactions, including queries and responses, are stored in `history.json` as a list of dictionaries for future reference.

### 📦 Requirements:
1. Install the necessary Python packages:
   - `pandas`
   - `google-generativeai`
   - `PyPDF2`
   - `python-dotenv`

2. Save your Google API key in a `.env` file using the following format:
   ```bash
   GOOGLE_API_KEY=your_api_key_here
   
📄 Make sure your files are in supported formats (.pdf, .txt, .csv) for successful upload and processing.
3. 🚀 Getting Started:
    -> Launch the Jupyter Notebook.
    -> Provide your query in the chatbot interface.
    -> Optionally upload a file to enhance the query.
    -> View the saved query and response history in history.json.
