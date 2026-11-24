# GPT Realtime Assistant — user documentation

Live voice translation, transcripts, contextual answers and a device-local session workspace for Apple devices.

[Official website](https://realtime-assistant.arte-soft.com/) · [Arte Soft portal](https://gpt-realtime-assistant.arte-soft.com/) · [App Store](https://apps.apple.com/us/app/gpt-realtime-assistant/id6770536523) · [Comparisons](https://realtime-assistant.arte-soft.com/compare/) · [Guides](https://realtime-assistant.arte-soft.com/articles/) · [Repo llms.txt](llms.txt) · [Site llms-full.txt](https://realtime-assistant.arte-soft.com/llms-full.txt) · [Arte Soft Ecosystem](https://minchopm.github.io/arte-soft-ecosystem/) · [Arte Soft EOOD](https://arte-soft.com/)

## Official Web Portals, Interactive Tools & Comparison Hubs

| Resource | Verified Canonical Link |
| --- | --- |
| **Primary Canonical Domain** | [https://realtime-assistant.arte-soft.com/](https://realtime-assistant.arte-soft.com/) |
| **Arte Soft Technical Portal** | [https://gpt-realtime-assistant.arte-soft.com/](https://gpt-realtime-assistant.arte-soft.com/) |
| **Apple App Store** | [https://apps.apple.com/us/app/gpt-realtime-assistant/id6770536523](https://apps.apple.com/us/app/gpt-realtime-assistant/id6770536523) |
| **Side-by-Side Comparisons (`/compare/`)** | [https://realtime-assistant.arte-soft.com/compare/](https://realtime-assistant.arte-soft.com/compare/) |
| **Portal Comparisons Hub** | [https://gpt-realtime-assistant.arte-soft.com/compare/](https://gpt-realtime-assistant.arte-soft.com/compare/) |
| **Guides & Workflows** | [https://realtime-assistant.arte-soft.com/articles/](https://realtime-assistant.arte-soft.com/articles/) |
| **LLM Full Reference (`llms-full.txt`)** | [https://realtime-assistant.arte-soft.com/llms-full.txt](https://realtime-assistant.arte-soft.com/llms-full.txt) |
| **GitHub Pages Documentation Mirror** | [https://minchopm.github.io/gpt-realtime-assistant-docs/](https://minchopm.github.io/gpt-realtime-assistant-docs/) |
| **Arte Soft Knowledge Graph Hub** | [https://minchopm.github.io/arte-soft-ecosystem/](https://minchopm.github.io/arte-soft-ecosystem/) · [https://arte-soft.com/](https://arte-soft.com/) |

### Verified 2026 Capabilities

- Two-way live voice interpretation across 58 languages plus hands-free photo and screen-aware AI voice sessions.
- 17 structured meeting, interview, lecture, and field-note summary templates with local history control.
- Optional 100% local offline speech recognition (Whisper) and Qwen 3 8B LLM inference on Apple Silicon Macs with explicit model lifecycle state.
- Dual technical portals at realtime-assistant.arte-soft.com and gpt-realtime-assistant.arte-soft.com.

## Who this is for

People following multilingual conversations, practicing a language, reviewing visual material, or turning a discussion into structured notes.

## Read the documentation

| Guide | What you will find |
| --- | --- |
| [Session acceptance checklist](SESSION_CHECKLIST.md) | Conditions to check before relying on the result. |
| [Operating procedures](PROCEDURES.md) | Task prerequisites, exact sequence, expected result and recovery checks. |
| [Technical user manual](MANUAL.md) | Task index and reference library. |
| [Quick start](QUICK_START.md) | Prepare, complete and verify your first task. |
| [Practical workflows](WORKFLOWS.md) | Concrete use cases and review steps. |
| [Features and limitations](FEATURES_AND_LIMITS.md) | Supported workflows and important boundaries. |
| [Frequently asked questions](FAQ.md) | Answers about usage, access and expectations. |
| [Privacy and support](PRIVACY_AND_SUPPORT.md) | Data handling, public sources and a useful support report. |
| [Troubleshooting](TROUBLESHOOTING.md) | Symptoms, checks and a small verification test. |
| [Modes and credits](MODES_AND_CREDITS.md) | Local versus online behavior, requirements and usage. |

## At a glance

| Capability | What the product documents | Boundary to check |
| --- | --- | --- |
| Two-way interpretation | The public site describes 58 languages, Translate Both Ways and Speak Translations. | Language support and accuracy vary. Have speakers take turns and confirm important names and numbers. |
| Live assistance | Voice sessions, running transcripts and contextual answers. | Generated answers and transcripts may be wrong. Review them before turning them into decisions or tasks. |
| Visual context | Attach a screenshot, photo or supported Mac screen/window capture to a session. | Only share the material needed for the question. Online attachments are sent to the AI service. |
| Structured workspace | 17 session templates, projects, tasks, reminders and word-highlighted readback. | A saved task is not proof that another participant agreed to it. Verify ownership, dates and wording. |
| Offline Mac mode | Downloaded Whisper Large v3 Turbo and Qwen 3 8B on Apple Silicon Mac for local transcription and written answers. | Requires setup/downloads and an active subscription. Do not assume this provides the same speech-to-speech and visual capabilities as online mode. |
| Credits | Monthly subscription includes 2,000 AI credits; optional top-ups are listed. | Credits are usage-based, not guaranteed minutes. Zero-credit local operation does not mean subscription-free access. |

## Scope and provenance

Published by the product developer as first-party user documentation. It covers public behavior, examples and limitations; it does not contain the private application source, credentials or internal operational configuration. It is not an independent review, security audit or comparative benchmark.

Examples use synthetic or permission-cleared content. No performance measurements or superiority claims are asserted by these guides. Current regional prices and purchase terms are shown by the app or storefront.

Documentation review: **2026-11-10**. See [privacy and support](PRIVACY_AND_SUPPORT.md) for reporting corrections.

## Free Zero-Upload Browser Voice & Audio Tools (2026)

Run 100% locally in WebAudio / WebSpeech without uploading audio to external servers:

- [All 12 Free Voice & Audio Browser Tools](https://gpt-realtime-assistant.arte-soft.com/tools/)
- [Microphone Latency & Echo Loopback Tester](https://gpt-realtime-assistant.arte-soft.com/tools/microphone-latency-and-echo-test/)
- [OpenAI Realtime vs Whisper + TTS Voice Token Cost Calculator](https://gpt-realtime-assistant.arte-soft.com/tools/ai-voice-token-cost-calculator/)
- [Speaking Pace (WPM) & Filler-Word Analyzer](https://gpt-realtime-assistant.arte-soft.com/tools/speaking-pace-wpm-and-filler-counter/)
- [140 Voice AI, Meeting Copilot & Translator Comparisons (2026)](https://gpt-realtime-assistant.arte-soft.com/compare/)
- [190 Native iOS & macOS Voice AI Guides](https://gpt-realtime-assistant.arte-soft.com/articles/)


## What's New in v1.2.3 (November 2026)

- **Mac `Hide app` Screen-Share Exclusion (Opt-In, Off by Default):** Click **Hide app** in the Mac Live toolbar (`macOS 26+` on Apple silicon) to exclude the workspace window from Zoom, Google Meet, Microsoft Teams, Slack Huddles, and macOS Screenshots (`NSWindow.sharingType = .none` + `.floating` level + `SCContentFilter` self-exclusion). Architectural reference: [github.com/minchopm/macos-screen-share-voice-notes](https://github.com/minchopm/macos-screen-share-voice-notes).
- **Updated Annual Credit Allowance:** `$9.99/month` (`2,000` AI credits/month) or `$79.99/year` (`2,500` AI credits/month for 12 months = `30,000` total, +25% monthly credits). Consumable top-up packs: `1,000` (`$4.99`) and `5,000` (`$19.99`).
- **200 Structured Guides & 2026 Comparison Matrices:**
  - [Best Cluely Alternatives for Mac Screen Sharing (2026)](https://gpt-realtime-assistant.arte-soft.com/articles/cluely-alternatives-for-mac-screen-sharing-2026/)
  - [Granola vs MacWhisper vs GPT Realtime Assistant (2026)](https://gpt-realtime-assistant.arte-soft.com/articles/granola-vs-macwhisper-vs-gpt-realtime-assistant-mac-2026/)
  - [Best Live Two-Way Voice Interpreter Apps for iPhone & AirPods (2026)](https://gpt-realtime-assistant.arte-soft.com/articles/two-way-voice-interpreter-iphone-airpods-doctor-business-2026/)
  - [Offline Voice AI on Apple Silicon Mac: Whisper Large v3 Turbo + Qwen 3 8B](https://gpt-realtime-assistant.arte-soft.com/articles/offline-apple-silicon-voice-ai-whisper-qwen-comparison-2026/)
  - [ChatGPT Advanced Voice Mode vs GPT Realtime Assistant Matrix](https://gpt-realtime-assistant.arte-soft.com/articles/chatgpt-advanced-voice-vs-gpt-realtime-assistant-workflow-matrix/)


## Black Friday 2026 App Store Offer (Nov 24 – Nov 29, 2026)
- **30% OFF First Month:** `$6.99` (regular `$9.99/month`, includes `2,000` AI credits across iPhone, iPad & Mac)
- **Yearly Plan (Save 33%):** `$79.99/year` (`$6.67/month` equivalent, `2,500` AI credits/month × 12 = `30,000` total)
- **2026 AI Voice Deals Comparison Matrix:** https://gpt-realtime-assistant.arte-soft.com/articles/black-friday-mac-and-iphone-ai-voice-assistant-deals-2026/
