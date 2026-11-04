# GPT Realtime Assistant — operating procedures

Use these procedures as task-oriented reference. They describe public capabilities and verification steps, not private implementation. UI labels can vary by version.

## Procedure 1: Turn a discussion into verified action items

### Before you begin

Use a meeting template appropriate to the discussion and tell participants that speech will be captured.

### Steps

1. State the required output: decisions, open questions and proposed tasks with owners and dates.

2. During the session, clearly distinguish a suggestion from an agreed decision.

3. Ask for a recap before the meeting ends and compare each item with the source conversation.

4. Confirm ambiguous names, deadlines and owners with the participants.

5. End the session explicitly and review the saved tasks and notes before distributing them.

### Expected result

The saved items reflect confirmed commitments; unsupported assumptions remain questions rather than decisions.

### If the result differs

If the recap invents an owner or date, correct it against the transcript and participant confirmation. A locally saved task is not evidence of agreement.

## Procedure 2: Commission offline Mac operation

### Before you begin

Use a supported Apple Silicon Mac, an active subscription and the documented model downloads.

### Steps

1. While online, complete model downloads and confirm the local transcription/answer mode.

2. Use fresh non-sensitive speech and confirm a transcript and written answer are produced.

3. Disable network connectivity deliberately for the test and start a new small session.

4. Speak a new sentence not present in the earlier history and check the new output.

5. Restore connectivity when the test is finished. Record device, app version, models and the result for future setup checks.

### Expected result

Fresh transcription and written answers work in the intended local mode without relying on cached history.

### If the result differs

If the test fails, check downloads, compatibility and mode selection. Do not silently switch a private session to online processing; voice output and visual context need their own capability checks.

## Report a repeatable problem

Record app/version, device/OS, selected mode, input conditions and the smallest failing step. Distinguish expected behavior from the observed result. Use synthetic examples and omit credentials or private records.

[Documentation index](README.md) · [Capabilities and limits](FEATURES_AND_LIMITS.md) · [Support and sources](PRIVACY_AND_SUPPORT.md)
