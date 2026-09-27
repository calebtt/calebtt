# Hi, I'm Caleb

Software engineer in Nashville, TN, writing C#/.NET, C++, and Python. I mostly build small, focused libraries and the tools on top of them.

Right now I'm working on voice agents that use a real phone line: SIP telephony, speech detection, echo cancellation, and the pieces that let an AI agent place and answer calls.

## Voice agents and telephony

- **[pbx-voice](https://github.com/calebtt/pbx-voice)**: a daemon that places phone calls for AI agents through your own SIP PBX. It handles wake-up alarms, spoken messages, and short goal-driven conversations, and agents request calls over MCP.
- **[SipBotLib](https://github.com/calebtt/SipBotLib)**: a headless SIP library for .NET, built on SIPSorcery, with a `sipbot` CLI for agents. It can register, answer, dial, transfer, send DTMF, and stream PCM audio.
- **[SipBotOpen](https://github.com/calebtt/SipBotOpen)**: a voice agent that answers incoming calls as a PBX extension. It runs speech-to-text and text-to-speech locally and uses an LLM with tool calling.
- **[MinimalSileroVad](https://github.com/calebtt/MinimalSileroVad)**: voice activity detection and speech segmentation for .NET, using the Silero VAD model (V4 and V5) on ONNX Runtime. It works with 8 kHz and 16 kHz audio.
- **[clean-speech](https://github.com/calebtt/clean-speech)**: a Linux microphone cleanup daemon. It cancels echo from system playback, suppresses noise, gates on speech, and publishes the result as a virtual microphone.
- **[MinimalDiarization](https://github.com/calebtt/MinimalDiarization)**: speaker diarization for .NET on ONNX Runtime, with experimental preprocessing for picking out voice commands in noisy rooms.
- **[MinimalVoiceAgent](https://github.com/calebtt/MinimalVoiceAgent)**: a minimal voice agent with tool calling, local speech-to-text and text-to-speech, and Grok over the xAI API.

## Model fine-tuning and inference

- **[MinimalTextClassifier](https://github.com/calebtt/MinimalTextClassifier)**: a binary text classifier for .NET on ONNX Runtime, with Python scripts for fine-tuning DeBERTa on your own data.
- **[youtube_skip_button_fine_tuned_yolo](https://github.com/calebtt/youtube_skip_button_fine_tuned_yolo)**: a fine-tuned YOLO11 model that detects YouTube "Skip ad" buttons, plus the data collection and training scripts.

Models are published on [Hugging Face](https://huggingface.co/calebt9990).

## C++

- **[XMapLib](https://github.com/calebtt/XMapLib)**: maps Xbox controller input to keyboard and mouse input on Windows, with rebindable keys and adjustable mouse sensitivity.
- **[impcool_sol](https://github.com/calebtt/impcool_sol)**: a thread pool for long-running tasks that uses immutability to keep the implementation simple.
- **[StreamToActionTranslator](https://github.com/calebtt/StreamToActionTranslator)**: the XMapLib keyboard core as a C++23 CMake library that turns an input stream into function calls, with unit tests.

## Contact

Email is the best way to reach me.
