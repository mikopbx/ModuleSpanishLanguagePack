# ModuleSpanishLanguagePack

Complete Spanish language pack for MikoPBX including UI translations and voice prompts.

## What's Included

- **Voice Prompts**: Spanish voice prompts for system menus, greetings, and notifications
- **UI Translations**: Complete Spanish translation of MikoPBX admin interface
- **Text Mapping**: `Sounds/core-sounds-es-es.txt` — text for TTS-generated prompts

## Installation

1. Download and install the module from MikoPBX Marketplace
2. Enable the module in **Modules** section
3. Go to **General Settings** and select Spanish (Español) as the system language

## Requirements

- MikoPBX 2025.1.1 or later

## TTS Attribution

All voice prompts in this pack are generated with neural TTS (Text-to-Speech) to provide a
consistent peninsular Spanish voice across the full set of MikoPBX system sounds:

- **Engine**: [Piper TTS](https://github.com/rhasspy/piper)
- **Voice model**: `es_ES-davefx-medium` (peninsular Spanish)
- **Sample rate**: 22050 Hz
- **Format**: WAV (PCM signed 16-bit, mono)

The text for each TTS-generated prompt is stored in `Sounds/core-sounds-es-es.txt` for
reference and regeneration. On module installation, MikoPBX automatically converts WAV
files to all Asterisk formats (ulaw, alaw, gsm, g722, sln) for codec compatibility.

## License

- Module code: GNU General Public License v3.0
- Sound files: CC BY-SA 4.0 (Asterisk Sound Files)
- TTS-generated sound files: CC BY-SA 4.0
- TTS engine: Piper TTS (https://github.com/rhasspy/piper)

## Copyright

- Module development: © 2017-2026 Alexey Portnov and Nikolay Beketov
- Voice prompts: From official Asterisk release where available
- TTS-generated voice prompts: Generated using open-source Piper TTS models
