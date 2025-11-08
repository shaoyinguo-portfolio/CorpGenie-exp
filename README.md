# CorpGenie: AI-Powered Meeting Insight Curation

## Project Background and Motivation

Meetings are vital for corporate decision-making and project reviews. However, information sharing is often inefficient in large organizations:

*   **Information Silos and Redundancy:** The same topics may be presented repeatedly, wasting time.
*   **Loss of Detail:** Information is often summarized, leading to misinterpretations.
*   **Lack of Context:** Teams may work in silos and duplicate efforts.

## The AI Solution

AI agents and Retrieval-Augmented Generation (RAG) systems can streamline corporate knowledge management. Simply using presentation files is not enough:

*   **Incomplete Data:** Slides lack detailed explanations.
*   **Contextual Gaps:** Working-level slides rely on the presenter's voice.

**CorpGenie addresses these gaps by capturing the full, multimodal context of a presentation.**

## Project Overview

This project demonstrates an end-to-end pipeline to curate knowledge, break silos, and boost efficiency:

1.  **Multimodal Data Capture:** Extracts visual frames and timestamped transcripts from meeting video recordings.
2.  **Contextual Alignment:** Aligns visual and audio data using timestamps.
3.  **LLM-Powered Document Generation:** Uses Vision-Language Models (VLMs), such as Gemini-2.0-flash or Qwen2.5-VL models, to analyze the synchronized inputs and rewrite them into coherent, accurate technical documents.
4.  **Vector Database and RAG System Integration:** The curated documents are indexed in a vector database for Retrieval-Augmented Generation. While conventional RAG is used for the Proof of Concept (PoC), GraphRAG is recommended for enhanced performance and richer context handling at a corporate scale.

**The goal is to feed this curated knowledge base into a robust RAG system, providing an intelligent AI agent that offers instant assistance during daily work and future meetings.**


## Data *Source*

The following YouTube video provides a good overview of the advanced semiconductor industry, and will be used for key frame and transcripts

[Sample YouTube video](https://www.youtube.com/watch?v=GfiaHEhFHaM)

[Download site](https://www.mediamister.com/free-youtube-video-downloader)
