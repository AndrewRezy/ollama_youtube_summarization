# Ollama Youtube Summarization
Youtube summarizer utilizing Ollama and Streamlit

## Usage (WIP)

### Docker

Easiest and quickest way to is build the container or download from docker hub (Coming Soon)
#### Build

`docker build -t ollama_youtube_summarization .`
#### Run (make sure to update the URL for your ollama host

`docker run -dit -p 8501:8501 -e OLLAMA_HOST_URL="http://10.0.0.1:11434" ollama_youtube_summarization`
