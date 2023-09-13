extend to support OpenAI Whisper
- connectors/ai/
  - open_ai/
    - services/
      - add open_ai_speech_transcription
    - __init__.py
      - add OpenAISpeechTranscription
  - add speech_transcription_client_base
  - __init__.py
    - add SpeechTranscriptionClientBase
- semantic_functions
  - add speech_prompt_template_config
  - add speech_prompt_template_base
  - add speech_transcription_prompt_template
- __init__.py
  - add SpeechTranscriptionPromptTemplate
- add speech/ for audio processing utils
  - add audio_chunker

add tests

Skills
  - add FileIO/
    - add audio_file_io
    - add text_file_io