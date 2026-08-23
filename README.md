# ascend-voice

A tiny top-level voice recorder page.

**The law of this repository: no PHI — no patient data of any kind — ever transits
or rests on this origin.** This page serves code only. In the planned v2, audio
flows directly from the browser to AWS transcription services under a signed BAA;
it never touches this host.

`index.html` — the recorder probe (mic permission, record, local playback).
`opener.html` — a test page for the popup/postMessage handback channel.
