# Tawalt — The Language AI Forgot

> NLP infrastructure for Tarifit Berber, a language spoken by 5M+ people with zero AI support.

## What is Tawalt?

Tawalt — Low-Resource NLP Infrastructure for the Maghreb
Bridging the gap for Tamazight & Maghrebi varieties. A specialized pipeline for languages with high conversational presence but zero native AI support.

🚀 Overview
Tawalt is a modular NLP infrastructure built to handle the unique linguistic challenges of Tarifit, Tashelhit, and Darija. Unlike generic models, Tawalt focuses on the "messy" reality of low-resource languages: orthographic inconsistency, code-switching, and phonetic depth.

📂 Core Projects
1. Tawalt Chatbot (Hugging Face)
An experimental conversational interface to evaluate LLM zero-shot capabilities in Tamazight.

Code-switching Resilience: Analyzes mixed-language inputs (Tamazight/French/Arabic).

Intent Mapping: Specialized detection for CX (Customer Experience) support flows.

Robustness: Integrated with rapidfuzz to handle non-standardized spelling.

2. Tarifit TTS Linguistic Frontend
A high-precision normalization pipeline designed to bridge the gap between informal text and acoustic models.

Expressive Normalization: Smart de-lengthening (reduces "azuuuul" to "azul") while preserving phonemic gemination (essential for natural prosody).

Phonetic Mapping: Converts "Chat-Arabic" numerals (7, 9, 3) and digraphs into a standardized phonemic layer.

Grammar-Aware: Protects clitics and pronouns during the normalization process to ensure morphological integrity.

Dataset Ready: Automatically generates CSV metadata aligned with LJSpeech standards.

3. Social Sentiment Analyzer
Advanced sentiment classification for low-resource social media data.

Noise Reduction: Specialized preprocessing for noisy Twitter/X datasets in Maghrebi dialects.

Emotion Detection: Differentiates between dialectal markers of intent and sentiment.

🛠️ Tech Stack & Methodology
Linguistic Engine: Python 3.10+ | spaCy 3.8

Normalization: RegEx-based phonemic mapping & Morphological protection.

Deployment: Hugging Face Spaces | Gradio.

Standards: Following AI4D (AI for Development) principles for responsible and inclusive AI.

## Author

Built by [@jamalinu](https://github.com/jamalinu)
