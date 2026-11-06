# Voice agents and caller preferences: call demo

**Page: https://tracy3057.github.io/voice-agent-preferences/**

Simulated phone calls between a voice caller (GPT-Live) and three full-duplex voice agents (GPT-Live, Grok Voice,
Gemini Live) on one τ²-bench airline task: move a flight to the next day, cheapest Economy. The caller is sad or happy
and wants a soft or an upbeat voice, and small talk before or after the flight change. The agent hears this in the call
(said or hinted), finds it in past calls or a memory note, or gets nothing.

- **Findings**: the main results and the numbers behind them.
- **Side by side**: the calls where the caller asks in plain words, by mood, request and agent.
- **Explore calls**: filter, compare and play every call (caller left channel, agent right), with transcripts and scores.

Static site: `index.html`, `data.json` (calls, transcripts, scores), `audio/*.mp3`. All callers are simulated.
