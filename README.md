# Hive QA Fixtures

Public test media fixtures for the Hive (thehive.ai) demo QA automation.

These files are publicly reachable so that the Hive demo **"Type or paste a valid media URL"**
upload path can be exercised end-to-end (the demo fetches media server-side, so URLs must
be public).

## speech/

All files contain the **same ~29.5 seconds of English speech** (transcript begins:
*"All these things that you can spend all your time consuming..."*), transcoded from
Hive's own demo sample `https://thehive.ai/images/72a2c7b.mp4`.

| File | Container / codec | Notes |
|---|---|---|
| `url-speech.wav`  | WAV / pcm_s16le | mono 44.1 kHz |
| `url-speech.mp3`  | MP3 / libmp3lame 128k | |
| `url-speech.ogg`  | Ogg / Vorbis | |
| `url-speech.flac` | FLAC | |
| `url-speech.m4a`  | MP4 audio / AAC 128k | |
| `url-speech.aiff` | AIFF / pcm_s16be | |
| `url-speech.mpeg` | MPEG audio / mp2 192k | |
| `url-speech.m4v`  | MP4 video / MPEG-4 + AAC | |
| `url-speech.h264` | raw H.264 stream (+AAC) | |

Raw URL pattern:

```
https://raw.githubusercontent.com/rachitajain2/hive-qa-fixtures/main/speech/<file>
```

These fixtures are mirrored from the private `chatous/hive-automation-qa` QA project.