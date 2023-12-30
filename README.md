# Faster Whisper Google Colab

A cloud deployment of [faster-whisper](https://github.com/guillaumekln/faster-whisper) on Google Colab. It leverages Google's cloud computing clusters and GPU to automatically generate subtitles (translation) or transcription for uploaded video files in various languages. Audio is first pre-processed using `ffmpeg` then processed with automatic speech recognition technology by OpenAI.


## Why use our tool? 
Firstly, its free! Other similar products, such as [Veed](https://www.veed.io/pricing), are paid services with restrictions on video length. We offer a completely free service with no restrictions on video length. 

Secondly, our tool significantly speeds up the runtime of Whisper compared to running it on our homelab. A [study](https://towardsdatascience.com/google-colab-how-does-it-compare-to-a-gpu-enabled-laptop-851c1e0a2ca9) has shown that despite being a free service, the GPU-enabled Google Colab environment (which is what we are using now) is significantly faster than a GPU-enabled MacBook Pro, Lenovo Legion and Lenovo Thinkpad, contributing to greater time savings. 

Thirdly, without the need to provision and maintain expensive hardware, users will also enjoy greater cost savings. Moreover, you will no longer have to worry about overheated machines or exorbitant electricity bills. 

Fourthly, we have an easy to use interface. No need to concern yourself with the complex technology of voice extraction and language translation. Just click and few buttons and you’re set. 

Lastly, our tool will also help the less fortunate, such as those with hearing disabilities, to decipher what is being spoken in videos and movies. 
## Getting Started
- Click on <a href="https://colab.research.google.com/github/ChanJianHao/Faster-Whisper-Google-Colab/blob/main/faster_whisper_youtube_drive.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> to open the notebook in Google Colab. <br>
- Follow the instructions on the notebook


### Output

When uploading, you will have to specify the extension of the output files (`srt` or `txt`). The output files can be found in the same directory as the uploaded video file. For example, if you uploaded a video file from `/content/drive/My Drive`, the subtitle file will also be found here.

### Updates

30 Dec 2023 - First release. Added direct download capability and support for other video file foromats like mkv.

## Acknowledgments

To be honest, I am not sure who made/contributed to this notebook originally; I only made some minor modifications to make it easier to download & translate, and fixed some bugs:
- ArthurFDLR
- lewangdev


