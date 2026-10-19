# cutroom-models

Model files mirrored for [Cutroom](https://github.com/vieraid/cutroom) so its setup can run where huggingface.co is blocked.

| Release asset | What it is | Source | License |
|---|---|---|---|
| `faster-whisper-small.tar` | Whisper *small*, CTranslate2 format (`config.json`, `model.bin`, `tokenizer.json`, `vocabulary.txt`) | [Systran/faster-whisper-small](https://huggingface.co/Systran/faster-whisper-small), converted from [openai/whisper](https://github.com/openai/whisper) | MIT (OpenAI Whisper; Systran conversion) |

Used by `setup.sh --with-model`, which extracts it to `~/.cache/cutroom/whisper/faster-whisper-small/`.
