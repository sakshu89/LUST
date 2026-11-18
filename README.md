# LUST — Android Phase 1

A clean, buildable Phase-1 foundation for a modular Android AI assistant.

### Included
- Jetpack Compose chat UI
- Provider abstraction
- Deterministic mock provider
- Basic calculator module
- Multi-module Gradle structure
- GitHub Actions Android build

### Build
```bash
./gradlew assembleDebug
```
If you are building on Android/Termux, use a Gradle distribution or Android build environment compatible with the installed JDK.

### Next phases
1. Local llama.cpp/LiteRT provider
2. Remote provider adapters
3. Agent planning/tool orchestration
4. Persistent memory/RAG
5. Voice/STT/TTS
6. Android integrations and accessibility
