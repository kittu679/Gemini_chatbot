# Gemini Pro ChatBot

A Streamlit-based chatbot powered by Google's Gemini Pro AI model.

## Setup Instructions

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Get Google API Key
1. Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create a new API key
3. Copy the API key

### 3. Configure Environment
1. Open the `.env` file in your project directory
2. Replace `your_actual_api_key_here` with your actual Google API key:
   ```
   GOOGLE_API_KEY=your_actual_google_api_key_here
   ```

### 4. Run the Application
```bash
streamlit run main.py
```

The application will open in your browser at `http://localhost:8501`

## Features
- Real-time chat interface with Gemini Pro
- Persistent chat history during session
- Clean, modern UI with Streamlit
- Markdown support for responses

## Troubleshooting

### Common Issues:
1. **"API key not found" error**: Make sure your `.env` file contains the correct API key
2. **Port already in use**: The app uses port 8501 by default. If it's busy, you can change it in `streamlit/config.toml`
3. **Module not found errors**: Ensure all dependencies are installed with `pip install -r requirements.txt`

### Getting Help:
- Check that your Google API key is valid and has access to Gemini Pro
- Ensure you have a stable internet connection
- Verify that all required packages are installed correctly 