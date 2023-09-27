#[ VOICE CLONING AND TRANSLATING](https://github.com/Ishaqinu/project_voice_cloning/blob/main/Voice_translate_and_cloning.ipynb)
A model for extract a voice of a speaker from diffrent languages and Clone the same speaker’s voice with the same pitch, and audio tone.
Whisper for Speech Translation: The script utilizes OpenAI's Whisper model to translate speech from Hindi to English. Whisper is a deep learning model designed for automatic speech recognition (ASR), making it capable of transcribing spoken words into text.
Tortoise TTS for Text-to-Speech: After translating the speech to English text, the project uses Tortoise TTS, a text-to-speech synthesis library. Tortoise TTS allows for the generation of speech using custom voices, which adds a personal touch to the synthesized audio.

## Overview

*Translation of Speech from Hindi to English: Your project involves translating speech from the Hindi language to English. You use OpenAI's Whisper model for speech translation.

*Text-to-Speech (TTS) with Custom Voices: After translating the speech to English, you generate speech audio using a custom voice. You have implemented a TTS system that allows for the synthesis of speech with custom voices. Users can upload audio clips to be used as custom voices.

*Project Dependencies and Installation: Your project requires several dependencies, including OpenAI's Whisper, specific Python packages (e.g., scipy, torchaudio), and the Tortoise TTS library.

*Input and Output Files: project deals with [input](https://github.com/Ishaqinu/project_voice_cloning/blob/main/input_hindi.wav) audio files in Hindi and generates [output](https://github.com/Ishaqinu/project_voice_cloning/blob/main/download.wav) audio files in English.

## Installation

```bash
# Example installation command
pip install git+https://github.com/openai/whisper.git
pip3 install -U scipy
git clone https://github.com/jnordberg/tortoise-tts.git
pip3 install -r requirements.txt:
tqdm
rotary_embedding_torch
transformers
tokenizers
inflect
progressbar
einops
unidecode
scipy
librosa
numba==0.48.0
ffmpeg
pip3 install transformers==4.19.0 einops==0.5.0 rotary_embedding_torch==0.1.5 unidecode==1.3.5
python3 setup.py install
