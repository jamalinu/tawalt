# Tawalt — The Language AI Forgot

> NLP infrastructure for Tarifit Berber, a language spoken by 5M+ people with zero AI support.

## What is Tawalt?

Tawalt is the first conversational NLP pipeline built natively for Tarifit Berber.
It processes, queues, and analyzes Tarifit text in real time using Python and spaCy.

## Projects

### 1. Tawalt Chat
The first chatbot that understands and responds in Tarifit Berber.

- Message queue architecture (FIFO)
- Tarifit vocabulary and grammar rules
- Automatic typo correction with rapidfuzz
- Intent detection (greetings, questions, farewells)
- Persistent conversation history (JSON)

👉 [Try it live](https://huggingface.co/spaces/jamalinu/tawalt)

### 2. Tarifit TTS Linguistic Frontend
A text normalization pipeline that prepares Tarifit text for Text-to-Speech synthesis.

- Converts informal Chat-Arabic numerals (7→ħ, 9→q, 3→ʕ)
- Maps digraphs to phonetic symbols (th→θ, gh→ɣ, kh→x)
- Detects and marks geminate consonants (ll→lː, rr→rː)
- Protects Amazigh pronouns during normalization
- Generates CSV metadata datasets for TTS training

## Tech Stack

- Python 3
- spaCy 3.8
- rapidfuzz
- phonemizer
- Google Colab

## Status

`v0.2 — Active development`

## Author

Built by [@jamalinu](https://github.com/jamalinu)
