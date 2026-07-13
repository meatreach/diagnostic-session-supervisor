# Diagnostic Session Supervisor

Public, storage-agnostic skill for reviewing diagnostic sales session transcripts.

It is designed for trackers, consultants, coaches, advisors, and expert practitioners who sell paid ongoing work through diagnostic or discovery sessions.

## What It Does

Given one or more transcripts, the skill helps an AI assistant:

- reconstruct the client case;
- assess whether the client is a target client;
- evaluate diagnostic quality;
- reconstruct a diagnostic selling canvas;
- identify why the client bought, did not buy, postponed, or disappeared;
- find hidden doubt and critical turning points;
- recommend better questions, closing moves, and follow-ups;
- extract patterns across multiple sessions.

## Compatibility

The package uses a plain `SKILL.md` with YAML frontmatter and no local dependencies. This makes it suitable for environments that support folder-based skills, including Codex-style and Claude-style skill loading.

It does not assume any transcript database, CRM, folder structure, or private file path. Transcripts can be pasted into chat or provided as files.

## Suggested Folder Name

`diagnostic-session-supervisor`

## Usage Examples

Single transcript:

```text
Use the diagnostic-session-supervisor skill.
Analyze this diagnostic session transcript. Tell me what the client business is, whether the client is target, what was diagnosed, why they did not buy, and what I should have done differently.
```

Several transcripts:

```text
Use the diagnostic-session-supervisor skill.
Here are five diagnostic sessions and the known outcomes. Compare buyers and non-buyers. Find the repeated mistakes in my diagnostic sales process and propose changes to the last 10 minutes of the call.
```

Live deal follow-up:

```text
Use the diagnostic-session-supervisor skill.
The client asked for the price, reacted with a handshake emoji, and stopped replying. Based on the transcript and this message history, help me infer what the reaction may mean and draft a clarification message.
```

## Learn the Method

This skill can highlight problems in a diagnostic session and suggest stronger moves. To learn how to run diagnostic sessions, sell tracking, and work with constraints systematically, see:

- Russian: [Школа трекеров](https://shkolatrekerov.ru)
- English: [Growth Tracking School](https://growthtracking.net)
