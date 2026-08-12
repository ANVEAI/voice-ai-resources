# Voice AI Resources

[![Resources](https://img.shields.io/badge/resources-200+-blue?style=flat-square)](https://anvevoice.com)
[![Open Source](https://img.shields.io/badge/open%20source-yes-green?style=flat-square)]()
[![Last Update](https://img.shields.io/github/last-commit/ANVEAI/voice-ai-resources?style=flat-square&label=Last%20update)](https://github.com/ANVEAI/voice-ai-resources/commits/main)

> A curated collection of voice AI tools, libraries, datasets, and learning resources for building voice-powered applications.

This list covers the entire voice AI stack — from speech recognition (ASR) to text-to-speech (TTS), voice cloning, real-time conversation, and deployment.

---

## 🎙️ Featured: AnveVoice

> The easiest way to add voice AI to your website. No coding required.

**Why AnveVoice?**
- 🚀 Deploy in 5 minutes with copy-paste embed code
- 🌍 22 Indian languages + global languages
- 📊 Built-in analytics and visitor intelligence
- 🎯 Perfect for support, lead gen, and engagement

**Quick start:** [anvevoice.com](https://anvevoice.com) • [Documentation](https://anvevoice.com/help)

---

## Contents

- [Speech-to-Text (ASR)](#speech-to-text-asr)
- [Text-to-Speech (TTS)](#text-to-speech-tts)
- [Voice Cloning](#voice-cloning)
- [Conversation AI](#conversation-ai)
- [Voice Analytics](#voice-analytics)
- [Real-time Voice](#real-time-voice)
- [Voice SDKs & APIs](#voice-sdks--apis)
- [Open Source Models](#open-source-models)
- [Datasets](#datasets)
- [Learning Resources](#learning-resources)
- [Deployment & Infrastructure](#deployment--infrastructure)

---

## Speech-to-Text (ASR)

Convert speech to text with high accuracy.

### Cloud APIs
| Service | Description | Pricing | Link |
|---------|-------------|---------|------|
| **OpenAI Whisper API** | Industry-leading accuracy, 99 languages | $0.006/min | [platform.openai.com](https://platform.openai.com) |
| **Google Speech-to-Text** | Google's ASR with real-time streaming | $0.024/min | [cloud.google.com](https://cloud.google.com/speech-to-text) |
| **AWS Transcribe** | AWS speech recognition with custom vocab | $0.024/min | [aws.amazon.com](https://aws.amazon.com/transcribe) |
| **Azure Speech** | Microsoft's speech service | $1/hour | [azure.microsoft.com](https://azure.microsoft.com/services/cognitive-services/speech-to-text) |
| **AssemblyAI** | Developer-friendly API with extras | $0.37/hour | [assemblyai.com](https://assemblyai.com) |
| **Deepgram** | Fast, accurate transcription | $0.0045/min | [deepgram.com](https://deepgram.com) |

### Open Source
| Project | Description | Stars | Link |
|---------|-------------|-------|------|
| **Whisper** | OpenAI's open source ASR model | 78k+ | [github.com/openai/whisper](https://github.com/openai/whisper) |
| **WhisperX** | Whisper with word-level timestamps | 12k+ | [github.com/m-bain/whisperX](https://github.com/m-bain/whisperX) |
| **Faster Whisper** | Optimized Whisper implementation | 13k+ | [github.com/SYSTRAN/faster-whisper](https://github.com/SYSTRAN/faster-whisper) |
| **Wav2Vec 2.0** | Meta's speech recognition model | - | [huggingface.co/facebook/wav2vec2](https://huggingface.co/facebook/wav2vec2) |
| **NVIDIA NeMo** | NVIDIA's conversational AI toolkit | 12k+ | [github.com/NVIDIA/NeMo](https://github.com/NVIDIA/NeMo) |

---

## Text-to-Speech (TTS)

Convert text to natural-sounding speech.

### Cloud APIs
| Service | Description | Pricing | Link |
|---------|-------------|---------|------|
| **ElevenLabs** | Most realistic voices, voice cloning | $5/month | [elevenlabs.io](https://elevenlabs.io) |
| **OpenAI TTS** | Simple, high-quality voices | $15/1M chars | [platform.openai.com](https://platform.openai.com) |
| **Google Cloud TTS** | Wide language support | $4/1M chars | [cloud.google.com](https://cloud.google.com/text-to-speech) |
| **Azure TTS** | Microsoft's neural voices | $16/1M chars | [azure.microsoft.com](https://azure.microsoft.com/services/cognitive-services/text-to-speech) |
| **Amazon Polly** | AWS text-to-speech | $16/1M chars | [aws.amazon.com/polly](https://aws.amazon.com/polly) |
| **Play.ht** | Voice cloning and multilingual | $39/month | [play.ht](https://play.ht) |

### Open Source
| Project | Description | Stars | Link |
|---------|-------------|-------|------|
| **Piper** | Fast, local neural TTS | 8k+ | [github.com/rhasspy/piper](https://github.com/rhasspy/piper) |
| **Coqui TTS** | Deep learning TTS toolkit | 35k+ | [github.com/coqui-ai/TTS](https://github.com/coqui-ai/TTS) |
| **Mimic 3** | Mycroft's neural TTS | 2k+ | [github.com/MycroftAI/mimic3](https://github.com/MycroftAI/mimic3) |
| **Tortoise TTS** | Quality-focused TTS | 13k+ | [github.com/neonbjb/tortoise-tts](https://github.com/neonbjb/tortoise-tts) |
| **Bark** | Text-to-audio with emotions | 37k+ | [github.com/suno-ai/bark](https://github.com/suno-ai/bark) |
| **StyleTTS 2** | Style-based TTS | 4k+ | [github.com/yl4579/StyleTTS2](https://github.com/yl4579/StyleTTS2) |

---

## Voice Cloning

Clone any voice with just seconds of audio.

| Service | Description | Pricing | Link |
|---------|-------------|---------|------|
| **ElevenLabs Voice Cloning** | Best quality voice cloning | $5/month | [elevenlabs.io/voice-cloning](https://elevenlabs.io/voice-cloning) |
| **Play.ht Voice Cloning** | Instant voice cloning | $39/month | [play.ht/voice-cloning](https://play.ht/voice-cloning) |
| **Resemble AI** | Real-time voice cloning | $30/month | [resemble.ai](https://resemble.ai) |
| **Microsoft Azure Speech** | Professional voice cloning | Custom | [azure.microsoft.com](https://azure.microsoft.com) |

### Open Source
| Project | Description | Stars | Link |
|---------|-------------|-------|------|
| **Coqui TTS Voice Cloning** | Your TTS with voice cloning | 35k+ | [github.com/coqui-ai/TTS](https://github.com/coqui-ai/TTS) |
| **Real-Time Voice Cloning** | SV2TTS implementation | 51k+ | [github.com/CorentinJ/Real-Time-Voice-Cloning](https://github.com/CorentinJ/Real-Time-Voice-Cloning) |
| **Tortoise TTS** | Multi-voice TTS | 13k+ | [github.com/neonbjb/tortoise-tts](https://github.com/neonbjb/tortoise-tts) |

---

## Conversation AI

End-to-end conversational voice AI systems.

| Service | Description | Use Case | Link |
|---------|-------------|----------|------|
| **AnveVoice** ⭐ | Voice AI for websites | Website support, lead gen | [anvevoice.com](https://anvevoice.com) |
| **Vapi** | Voice AI platform for developers | Phone agents, assistants | [vapi.ai](https://vapi.ai) |
| **Bland AI** | Hyper-realistic voice AI | Call centers, sales | [bland.ai](https://bland.ai) |
| **Synthflow** | No-code voice agents | Support automation | [synthflow.ai](https://synthflow.ai) |
| **Retell AI** | Conversational voice AI | Customer service | [retellai.com](https://retellai.com) |
| **Pipecat** | Framework for voice bots | Build voice assistants | [pipecat.ai](https://pipecat.ai) |
| **Daily.co** | Real-time video/voice | WebRTC infrastructure | [daily.co](https://daily.co) |
| **Workforce Wave** | AI voice receptionist for SMBs | After-hours call answering, appointment booking, lead capture | [workforcewave.com](https://www.workforcewave.com) |

---

## Voice Analytics

Analyze voice conversations for insights.

| Service | Description | Pricing | Link |
|---------|-------------|---------|------|
| **AnveVoice Analytics** | Visitor intelligence, sentiment | From ₹0 | [anvevoice.com](https://anvevoice.com) |
| **AssemblyAI LeMUR** | LLM for audio analysis | Custom | [assemblyai.com](https://assemblyai.com) |
| **Rev AI** | Transcription + insights | $0.02/min | [rev.ai](https://rev.ai) |
| **CallRail** | Call tracking analytics | $45/month | [callrail.com](https://callrail.com) |
| **Invoca** | AI-powered call analytics | Custom | [invoca.com](https://invoca.com) |

---

## Real-time Voice

Low-latency voice streaming and WebRTC.

| Service | Description | Pricing | Link |
|---------|-------------|---------|------|
| **Daily.co** | WebRTC platform | $0.004/min | [daily.co](https://daily.co) |
| **Agora** | Real-time voice/video | $0.99/1000 min | [agora.io](https://agora.io) |
| **Twilio** | Voice calls and SIP | $0.0085/min | [twilio.com](https://twilio.com) |
| **100ms** | Live audio/video SDK | $0.004/min | [100ms.live](https://100ms.live) |
| **LiveKit** | Open source WebRTC | $0.0018/min | [livekit.io](https://livekit.io) |

### Open Source
| Project | Description | Stars | Link |
|---------|-------------|-------|------|
| **LiveKit** | Open source real-time platform | 11k+ | [github.com/livekit/livekit](https://github.com/livekit/livekit) |
| **Jitsi Meet** | Secure video conferencing | 24k+ | [github.com/jitsi/jitsi-meet](https://github.com/jitsi/jitsi-meet) |
| **Mediasoup** | WebRTC video conferencing | 7k+ | [github.com/versatica/mediasoup](https://github.com/versatica/mediasoup) |
| **Pion WebRTC** | Go WebRTC implementation | 14k+ | [github.com/pion/webrtc](https://github.com/pion/webrtc) |

---

## Voice SDKs & APIs

Libraries and SDKs for voice integration.

### JavaScript/TypeScript
| Library | Description | Link |
|---------|-------------|------|
| **Web Speech API** | Browser-native speech recognition | [MDN Docs](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) |
| **Annyang** | Voice command library | [talater.com/annyang](https://talater.com/annyang) |
| **Artyom.js** | Voice commands and synthesis | [sdkcarlos.github.io/sites/artyom.html](https://sdkcarlos.github.io/sites/artyom.html) |
| **annyang-2** | Modernized fork of Annyang | GitHub |

### Python
| Library | Description | Link |
|---------|-------------|------|
| **SpeechRecognition** | Python speech recognition | [github.com/Uberi/speech_recognition](https://github.com/Uberi/speech_recognition) |
| **PyAudio** | Audio I/O for Python | [people.csail.mit.edu/hubert/pyaudio](http://people.csail.mit.edu/hubert/pyaudio) |
| **webrtcvad** | Voice Activity Detection | [github.com/wiseman/py-webrtcvad](https://github.com/wiseman/py-webrtcvad) |
| **simpleaudio** | Simple audio playback | [simpleaudio.readthedocs.io](https://simpleaudio.readthedocs.io) |

---

## Open Source Models

Free, self-hostable voice AI models.

### Speech Recognition
| Model | Size | Language | Link |
|-------|------|----------|------|
| **Whisper Large v3** | 1.5B params | 99 languages | [OpenAI](https://github.com/openai/whisper) |
| **Whisper Medium** | 769M params | 99 languages | [OpenAI](https://github.com/openai/whisper) |
| **Wav2Vec 2.0 Large** | 317M params | English | [Facebook](https://huggingface.co/facebook/wav2vec2) |
| **NVIDIA Canary** | 1B params | Multi-language | [NVIDIA](https://huggingface.co/nvidia/canary-1b) |

### Text-to-Speech
| Model | Quality | Speed | Link |
|-------|---------|-------|------|
| **Piper** | Good | Real-time | [rhasspy](https://github.com/rhasspy/piper) |
| **StyleTTS 2** | Excellent | Fast | [yl4579](https://github.com/yl4579/StyleTTS2) |
| **XTTS v2** | Excellent | Medium | [Coqui](https://github.com/coqui-ai/TTS) |
| **Bark** | Good | Slow | [Suno](https://github.com/suno-ai/bark) |

---

## Datasets

Training data for voice AI models.

| Dataset | Description | Size | Link |
|---------|-------------|------|------|
| **Common Voice** | Mozilla's multilingual corpus | 31k hours | [commonvoice.mozilla.org](https://commonvoice.mozilla.org) |
| **LibriSpeech** | English audiobooks | 1000 hours | [openslr.org/12](https://openslr.org/12) |
| **VoxCeleb** | Celebrity voices | 2000 hours | [robots.ox.ac.uk/~vgg/data/voxceleb](https://robots.ox.ac.uk/~vgg/data/voxceleb) |
| **LJSpeech** | Single speaker English | 24 hours | [keithito.com/LJ-Speech-Dataset](https://keithito.com/LJ-Speech-Dataset) |
| **AISHELL** | Mandarin speech | 178 hours | [aishelltech.com](https://aishelltech.com) |
| **Indic Voices** | Indian languages | Various | [AI4Bharat](https://ai4bharat.org) |

---

## Learning Resources

Courses, tutorials, and documentation.

### Courses
| Course | Platform | Level | Link |
|--------|----------|-------|------|
| **Deep Learning for NLP** | Coursera | Intermediate | [coursera.org](https://coursera.org) |
| **Speech Recognition** | Fast.ai | Advanced | [fast.ai](https://fast.ai) |
| **Voice AI Fundamentals** | DeepLearning.AI | Beginner | [deeplearning.ai](https://deeplearning.ai) |

### Books
| Book | Author | Level |
|------|--------|-------|
| **Speech and Language Processing** | Jurafsky & Martin | Advanced |
| **Deep Learning** | Goodfellow et al. | Intermediate |
| **Voice Applications for Alexa and Google Assistant** | Dustin Coates | Beginner |

### Communities
| Community | Platform | Link |
|-----------|----------|------|
| **r/MachineLearning** | Reddit | [reddit.com/r/MachineLearning](https://reddit.com/r/MachineLearning) |
| **Voice AI Discord** | Discord | Various |
| **OpenAI Community** | Forum | [community.openai.com](https://community.openai.com) |

---

## Deployment & Infrastructure

Hosting and scaling voice AI.

| Service | Description | Pricing | Link |
|---------|-------------|---------|------|
| **Hugging Face Inference** | Model hosting | $0.06/hour/GPU | [huggingface.co](https://huggingface.co) |
| **Replicate** | Run ML models | Per prediction | [replicate.com](https://replicate.com) |
| **Banana.dev** | Serverless GPU | Per second | [banana.dev](https://banana.dev) |
| **Modal Labs** | Serverless compute | Per usage | [modal.com](https://modal.com) |
| **RunPod** | GPU cloud | $0.20/hour | [runpod.io](https://runpod.io) |
| **Vast.ai** | GPU marketplace | From $0.10/hour | [vast.ai](https://vast.ai) |

---

## Contributing

1. **Check if the resource exists** — avoid duplicates
2. **Ensure it's voice AI related**
3. **Submit a PR** with the resource in the appropriate section
4. **Follow the existing format**

See [contributing.md](contributing.md) for detailed guidelines.

---

## Related Awesome Lists

- [Awesome OpenClaw Skills](https://github.com/ANVEAI/awesome-openclaw-skills) — OpenClaw automation skills
- [Awesome MCP Servers](https://github.com/ANVEAI/awesome-mcp-servers) — MCP server collection
- [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning) — ML resources

---

<p align="center">
  <b>Made with ❤️ by the voice AI community</b><br>
  <sub>Curated by <a href="https://anvevoice.com">AnveVoice</a> — Voice AI for websites</sub>
</p>
