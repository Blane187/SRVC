
[![License](https://img.shields.io/github/license/liujing04/Retrieval-based-Voice-Conversion-WebUI?style=for-the-badge)](https://github.com/liujing04/Retrieval-based-Voice-Conversion-WebUI/blob/main/LICENSE.txt)

[![Huggingface](https://img.shields.io/badge/🤗%20-Spaces-yellow.svg?style=for-the-badge)](https://huggingface.co/lj1995/VoiceConversionWebUI/tree/main/)

[![Discord](https://img.shields.io/badge/RVC%20Developers-Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)]()

[![Open In Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)](https://colab.research.google.com/drive/1iWOLYE9znqT6XE5Rw2iETE19ZlqpziLx?usp=sharing)

# Installation of dependencies 🖥️
Using pip (python3.9.8 is recommended)
```bash
python -m venv env
pip install -r requirements.txt
```

## Local Usage

Here is the list of files necessary to run the program:
You can download the first two from [Huggingface space](https://huggingface.co/lj1995/VoiceConversionWebUI/tree/main/).

```bash
hubert_base.pt

rmvpe.pt
#If you're using Windows, you need this file; skip if ffmpeg ffpbobe are installed; Ubuntu/Debian users can install these two libraries through apt install ffmpeg

./ffmpeg

./ffprobe
```

## Credits
+ [ContentVec](https://github.com/auspicious3000/contentvec/)
+ [VITS](https://github.com/jaywalnut310/vits)
+ [HIFIGAN](https://github.com/jik876/hifi-gan)
+ [Gradio](https://github.com/gradio-app/gradio)
+ [FFmpeg](https://github.com/FFmpeg/FFmpeg)
+ [Ultimate Vocal Remover](https://github.com/Anjok07/ultimatevocalremovergui)
+ [audio-slicer](https://github.com/openvpi/audio-slicer)
+ [Mangio FORK](https://github.com/Mangio621/Mangio-RVC-Fork)
