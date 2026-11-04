# GPT Realtime Assistant — modes and credits

## Two different processing workflows

| Workflow | Where processing occurs | Setup and access | What not to assume |
| --- | --- | --- | --- |
| Online voice/translation | Audio and supplied session context go to OpenAI | Internet, active subscription and available credits | Device-local saved notes do not make online inference local |
| Local Mac transcription and written answers | Downloaded Whisper and Qwen models on Apple Silicon Mac | Compatible Mac, model downloads and active subscription; zero AI credits for local operation | Do not assume identical voice-output, vision or mobile capabilities |

Choose the workflow before sharing sensitive content. If a local workflow is unavailable, switching to online changes the recipient of the data. Treat that as a deliberate user decision.

## Prepare local mode before you need it

Download the supported models while online. Check storage and make a short non-sensitive transcription test. Then repeat with network connectivity unavailable and verify both fresh transcription and written answers. A previous transcript remaining visible is not an offline processing test.

Use a small session to judge whether the device can keep up with your speaking pace. This documentation publishes no speed or memory requirements beyond the official compatibility description. Do not extrapolate performance from a different Mac or model version.

## Credits are usage, not time

The public plan includes 2,000 monthly AI credits and optional consumable top-ups. Audio and text usage, selected model rates and session behavior affect consumption. A fixed credit balance does not guarantee a fixed conversation duration.

Before starting, note the displayed balance. End the session explicitly when finished; the site describes a reservation-and-refund mechanism for unused session reservations. Compare the resulting balance in the app. A temporary reservation should not automatically be interpreted as final consumed usage.

A top-up adds credits; it does not replace the required subscription. Likewise, zero-credit local mode is not described as subscription-free access. Check current regional prices, renewal terms and entitlements in the purchase interface rather than relying on a price quoted in a guide.

## Choose a session purpose

For conversation translation, set both languages and the spoken-translation option. For a meeting, use a template and specify the desired output, such as proposed decisions and tasks. For visual questions, attach only the necessary screenshot or photo. Ask for clarification when the transcript or image does not contain enough evidence.

Review names, numbers and action-item owners before relying on generated content. A task saved locally is still a draft if it was inferred rather than agreed by participants.

[Documentation home](README.md) · [Privacy and support](PRIVACY_AND_SUPPORT.md) · [Official site](https://realtime-assistant.arte-soft.com/)

Reviewed 2026-11-04. This app is independently published by Arte Soft, not OpenAI.
