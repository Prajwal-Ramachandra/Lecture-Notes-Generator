# Lecture-Notes-Generator using Langchain
A tool to process lecture videos and the corresponding lecture slides and generate a conslidated Lecture Notes PDF.

# Features
1. Uses OpenAI's Whisper model to generate transcripts of the video.
2. Generates embeddings of the transcripts and saves in Chromadb.
3. Extracts various fields and content from PPT and stores it in a json file.
4. Uses Langchain to generate the notes PDF from the two sources.

# Steps to run the code
Generate Groq API key and save it in key.txt
