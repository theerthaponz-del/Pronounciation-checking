Pronounciation-checking

This project evaluates English word pronunciation by comparing phoneme sequences derived from spoken audio with the correct phonetic form. It integrates OpenAI Whisper for speech-to-text transcription and g2p_en for grapheme-to-phoneme conversion, allowing the system to score pronunciation accuracy based on phoneme similarity.

Features:

Automatic speech recognition using Whisper
Phoneme extraction and comparison using G2P
Pronunciation scoring based on phonetic similarity
Handles vowel variations and provides feedback on pronunciation quality

Dataset:
The dataset includes recorded single-word English audio samples (e.g., eat, bait, bat) from different speakers to capture accent and pronunciation variations. Each clip is labeled with the corresponding text for reference.

Usage:
Upload an audio file (WAV/MP3/M4A).
Specify the expected word (e.g., "bait").
The model transcribes speech, extracts phonemes, compares them, and outputs a pronunciation score with qualitative feedback.

Dependencies:
openai-whisper
whisperx
g2p_en
pronouncing
