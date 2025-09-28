# Huberman Podcast Summarizer

End-to-end pipeline that downloads Huberman Lab podcast episodes, transcribes audio with Whisper, summarizes with GPT-4o mini, and enables semantic search across episodes via a RAG chatbot.

## Notebooks

1. `1_HubermanLab_Summarizer.ipynb` — downloads audio and creates transcripts.  
2. `2_HubermanLab_RAG_Chatbot.ipynb` — builds a RAG chatbot with semantic search.  

## Requirements

See `requirements.txt` for all needed packages.
