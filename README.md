
# Search in Video Plug-in


Imagine the challenge of finding specific information in long videos, which can be frustrating and inefficient. But picture this solution: a search tool where users can type in keywords related to what they're looking for. This feature would quickly guide them to the right parts of the video, making it easier to find what they need and improving their overall experience.

## Application Overview

The application employs Flask, a Python web framework, to provide a user-friendly interface for uploading videos and searching for segments.
Users can upload local video files or specify YouTube video links for processing.
Upon upload, the application extracts audio from videos and utilizes PVleopard for speech-to-text (STT) conversion, generating transcriptions for further analysis.
Leveraging NLP techniques, such as Spacy for linguistic processing and BERT models for semantic similarity calculations, the application enables users to search for specific sentences or phrases within the video transcriptions.
It employs cosine similarity to find the most relevant segments based on user queries, allowing seamless navigation through video content.
The application seamlessly handles both local video files and YouTube videos, accommodating diverse user preferences.
For YouTube videos, it utilizes the YouTube Transcript API to retrieve transcripts if available, or alternatively processes audio using PVleopard for transcription extraction.
The project demonstrates a modular architecture, with plans to support additional platforms like Coursera videos in the future.
This extensibility showcases a forward-looking approach, ensuring scalability and adaptability to evolving user needs and technological advancements.


## Tech Stack


**FrontEnd:** HTML , CSS , JavaScript

**FrameWork:** Flask (for backend development)

**Liraries:** spacy, moviepy, youtube_transcript_api, pvleopard , pytube , Cosine Similarity Search 




## References

 - [Attention Is All You Need](https://papers.neurips.cc/paper/7181-attention-is-all-you-need.pdf)
 - [Embeddings](https://en.wikipedia.org/wiki/Sentence_embedding)
 - [Cosine Similarity](https://en.wikipedia.org/wiki/Cosine_similarity)

