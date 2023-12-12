# YouTube Video Summarizer

This Python script extracts and summarizes information from a YouTube video using various libraries.

## Overview

This script performs the following tasks:
- Extracts the video ID from a YouTube URL using `pytube`.
- Retrieves the video transcript using the `YouTubeTranscriptApi`.
- Utilizes spaCy for natural language processing to analyze the transcript.
- Identifies key sentences and generates a summary using heapq.

## Prerequisites
```bash
pip install pytube youtube-transcript-api spacy
python -m spacy download en_core_web_sm
```
## Usage
Replace the video_url variable with the YouTube video URL you want to summarize. Then run the script.

## Output
The script generates a summary of the video content based on the identified key sentences.

## Acknowledgments
- Educative.io
- pytube for YouTube video extraction.
- youtube-transcript-api for accessing YouTube transcripts.
- spaCy for natural language processing.
- heapq for extracting the most significant sentences.
