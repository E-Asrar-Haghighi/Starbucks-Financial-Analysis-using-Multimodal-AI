# Starbucks Financial Analysis using Multimodal AI

## Overview
This project applies **multimodal AI techniques** to analyze **Starbucks' financial performance** using a combination of **text, images, and audio**. It integrates **Whisper, CLIP, and GPT-4o-mini** to extract insights from earnings call transcripts, financial statements, and reports.

## Features
- **Speech-to-Text Transcription**: Converts earnings call audio into text using **OpenAI Whisper**.
- **Text & Image Embedding**: Processes financial transcripts and reports using **CLIP Sentence Transformers**.
- **Similarity-Based Retrieval**: Finds the most relevant text and images based on user queries.
- **AI-Generated Financial Insights**: Uses **GPT-4o-mini** to generate responses based on extracted financial data.


### Steps in the Notebook:
1. **Setup Environment**: Installs dependencies and mounts Google Drive.
2. **Transcribe Audio**: Converts the earnings call into text.
3. **Embed Transcription & Images**: Uses **CLIP** to encode data.
4. **Retrieve Relevant Data**: Matches user queries with financial text and images.
5. **Generate AI Insights**: Uses **GPT-4o-mini** to answer financial questions.

## Example Query
Modify the query in the notebook to extract insights:
```python
query = "Why is the company revenue declining?"
```
The AI will retrieve relevant financial statements and generate an insightful response.

**This project is part of the RAG, AI Agents and Generative AI with Python and OpenAI 2025 from Udemy**


## License
This project is licensed under the **MIT License**.



