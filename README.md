# AI Meeting Assistant

A project concept for turning meeting recordings and online videos into structured, searchable notes.

## Intended workflow

The documented product direction is to accept a YouTube URL or an audio/video file and produce:

- A transcript
- A concise meeting summary
- Action items with owners and deadlines when they can be identified
- Key decisions and unresolved questions
- Contextual question answering over the meeting content
- PDF and TXT exports

## Proposed technology

The original project notes list Python, Streamlit, LangChain, ChromaDB, Whisper, Mistral AI, Sarvam AI, and Docker.

## Repository status

**This repository currently contains project documentation only.** The application source code, dependency manifest, setup scripts, and runnable demo are not present in the default branch yet. The feature list above describes the documented direction, not a verified working implementation.

## Suggested implementation milestones

1. Add a minimal Streamlit application and supported input handling.
2. Implement transcription with clear model and language configuration.
3. Add structured summarization and action-item extraction.
4. Add session-isolated retrieval and transcript-grounded Q&A.
5. Add export functionality, tests, and deployment documentation.

## Author

**Saksham Singh** · [GitHub](https://github.com/sakshamsingh22)
