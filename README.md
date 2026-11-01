# Supertonic 3 voice styles

A collection of custom voice styles trained for [Supertonic 3](https://github.com/supertone-oss-archive/supertonic). Each voice will have a JSON style file and an MP3 sample so you can listen before downloading.

This is an independent project and is not affiliated with Supertone.

## Voices

No voices have been published yet. When they are available, you can find the style files in [`voices/`](voices/) and listen to the samples in [`previews/`](previews/). Matching files will share the same name, for example `voices/example.json` and `previews/example.mp3`.

## Using a voice

Download a JSON file from `voices/` and load it as a custom voice style in a Supertonic 3-compatible application. For example, the [Supertonic Python package](https://github.com/supertone-oss-archive/supertonic-py) accepts a custom style path:

```bash
pip install supertonic
supertonic tts "Hello, world!" --custom-style-path voices/example.json -o output.wav
```

Replace `voices/example.json` with the path to the downloaded file. The first run downloads the Supertonic model; this repository does not include it.

## Licenses and responsible use

Unless a voice is marked otherwise, the repository owner's rights in the JSON voice styles and MP3 samples are licensed under [CC BY-NC 4.0](LICENSE). Where copyright or similar rights apply, this permits sharing and adapting the files for noncommercial purposes with attribution. Please credit **ivan23456-super** and link to this repository and the license.

This license only covers rights the repository owner can grant. It does not grant rights to another person's voice or recordings, or replace third-party terms. Check the permissions and conditions for each voice before publishing or using it. Do not use generated speech to deceive or impersonate someone without consent.

Supertonic's code and model have separate licenses: the example code is MIT-licensed and the model is distributed under OpenRAIL-M. See the [upstream project](https://github.com/supertone-oss-archive/supertonic) and the [model license](https://huggingface.co/supertone-oss-archive/supertonic-3/blob/main/LICENSE) for their terms. The model's use restrictions still apply when using it; check whether its redistribution terms also apply to a particular voice style.
