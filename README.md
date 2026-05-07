Project: Bridge Voice

Tech Stack:

* React 19
* TypeScript
* Vite
* TailwindCSS
* Google Gemini APIs
* Gemini Live API
* Gemini TTS
* Web Audio API

Project Type:
Real-time AI-powered multilingual speech-to-speech translation platform with emotion-aware voice synthesis.

Core Features:

* Real-time speech translation
* Emotion detection and preservation
* AI-generated translated voice
* Speaker mode
* Listener mode
* Live microphone streaming
* PCM audio processing
* Multilingual support
* Modern responsive UI

IMPORTANT RULES:

1. Do NOT rewrite the whole project unnecessarily.
2. Preserve existing UI design and architecture.
3. Do NOT remove Gemini integration.
4. Do NOT replace TypeScript with JavaScript.
5. Do NOT break Tailwind styling.
6. Keep all existing components working.
7. If fixing one file affects another file, explain dependency changes clearly.
8. Return COMPLETE updated files, not partial snippets.
9. Do NOT use placeholders like:
   // rest of code
   // existing logic
10. Maintain compatibility with:

* React 19
* Vite
* TypeScript strict mode

Project Architecture:

* App.tsx
* components/

  * Layout.tsx
  * SpeakerView.tsx
  * ListenerView.tsx
  * DemoView.tsx
  * Onboarding.tsx
* services/

  * geminiService.ts
* types.ts

AI Workflow:
Voice Input
→ Speech Recognition
→ Emotion Detection
→ Translation
→ AI Text-to-Speech
→ Audio Playback

If you get stuck:

* First identify the exact error source
* Check imports/exports carefully
* Check async audio streaming logic
* Check TypeScript types/interfaces
* Check Gemini API response formats
* Check AudioContext/browser permission issues
* Avoid changing architecture unless absolutely necessary

When responding:

* Explain what caused the error
* Give exact file changes
* Return complete corrected code for affected files
* Preserve all current functionality
