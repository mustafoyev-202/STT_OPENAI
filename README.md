# 🎙️ Audio Processing Application

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![OpenAI](https://img.shields.io/badge/OpenAI-API-green.svg)](https://openai.com/)
[![Streamlit](https://img.shields.io/badge/Streamlit-Framework-red.svg)](https://streamlit.io/)

A powerful audio processing application that transcribes, analyzes, and translates conversations with speaker diarization support. Available in both Uzbek and English interfaces.

## 🌟 Features

- **Audio Transcription**: Utilizes OpenAI's Whisper model for accurate speech-to-text conversion
- **Speaker Diarization**: Automatically identifies and labels different speakers in conversations
- **Language Processing**: 
  - Handles mixed Kazakh-Uzbek conversations
  - Translates to pure Uzbek while preserving original structure
- **Smart Analysis**: 
  - Generates comprehensive conversation summaries
  - Identifies key topics and points
  - Analyzes speaker patterns and interactions
- **User-Friendly Interface**:
  - Intuitive file upload system
  - Real-time processing status
  - Downloadable results in multiple formats

## 🚀 Getting Started

### Prerequisites

```bash
python >= 3.8
openai
streamlit
python-dotenv
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/mustafoyev-202/OPENAI_STT.git
cd audio-processor
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the root directory:
```env
OPENAI_API_KEY=your_openai_api_key_here
```

### Running the Application

```bash
streamlit run app.py
```

For the English version:
```bash
streamlit run main.py
```

## 💡 Usage

1. Launch the application using the command above
2. Upload an audio file (supported formats: MP3, WAV, M4A)
3. Wait for the processing to complete
4. View the results:
   - Original transcription
   - Speaker-labeled conversation
   - Translated text (for Uzbek version)
   - Conversation analysis and summary
5. Download the results using the provided buttons

## 🔧 Configuration

The application can be configured through environment variables:
- `OPENAI_API_KEY`: Your OpenAI API key (required)
- Additional Streamlit configurations can be set in `.streamlit/config.toml`

## 🌍 Language Support

### Uzbek Version (app.py)
- Transcribes mixed Kazakh-Uzbek conversations
- Translates to pure Uzbek
- Provides interface in Uzbek language

### English Version (main.py)
- Transcribes English conversations
- Provides interface in English language
- Focuses on speaker diarization and analysis

## 🔍 Technical Details

The application uses several advanced technologies:
- **OpenAI Whisper**: For accurate speech-to-text conversion
- **GPT-4**: For speaker diarization and text analysis
- **Streamlit**: For the web interface
- **Regular Expressions**: For text formatting and cleaning

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Important Notes

- Ensure your audio files are clear and of good quality
- Large audio files may take longer to process
- API usage is subject to OpenAI's pricing and rate limits

## 🙏 Acknowledgments

- OpenAI for providing the API services
- Streamlit for the awesome framework
- Contributors and users of this application

