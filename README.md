# good-news-audio

Generated Telugu narration for [Good News Daily](https://anilkumarnandamuri.github.io/good-news-daily/),
served by GitHub Pages at https://anilkumarnandamuri.github.io/good-news-audio/

- `manifest.json` — story id -> clip map read by the site's reader.
- `te/<hash>.mp3` — one mono ~32 kbps MP3 per Telugu summary, named by a hash of the voice + text
  (immutable). Clips no longer referenced are deleted after 7 days.

Generated automatically by `scripts/tts_audio.py` in good-news-daily; do not edit by hand.

## Licences
- Synthesised with [Piper](https://github.com/OHF-voice/piper1-gpl) (GPL-3.0; used as an offline tool,
  the generated audio is not covered by the GPL).
- Voice: `te_IN-maya-medium` from [rhasspy/piper-voices](https://huggingface.co/rhasspy/piper-voices),
  trained on the IIT Madras Indic TTS database (Speech Technology Consortium, IIT Madras), whose licence
  grants a perpetual, worldwide, royalty-free licence and permits free distribution of derivative works.
- Narrated text: the public story summaries published by Good News Daily.
