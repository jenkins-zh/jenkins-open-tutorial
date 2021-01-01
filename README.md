![GitHub contributors](https://img.shields.io/github/contributors/jenkins-zh/jenkins-open-tutorial)
[![HitCount](http://hits.dwyl.com/jenkins-zh/jenkins-open-tutorial.svg)](http://hits.dwyl.com/jenkins-zh/jenkins-open-tutorial)

# Jenkins Open Tutorial
This is an open tutorial for Jenkins

# Video
We use [openshot](https://github.com/OpenShot/openshot-qt) as the tool for video clip.

Output format:

| Item | Description |
|---|---|
| Target | mp4(h.264) |
| Video Profile | HD 1080p 30fps |

Header video: 2s

Tail video: 8s + 2s

## Plugins for openshot
In order to have the advanced editor of title, please install [inkscape](https://inkscape.org/).

### For Ubuntu users
```
sudo add-apt-repository ppa:inkscape.dev/stable
sudo apt update
sudo apt install inkscape
```

# Subtitle
Please submit the subtitle file into [this directory](openshot). These subtitle files should keep the same name with openshot project files. For example, `xxx.osp` and `xxx.srt` have the same prefix.

There are [many different format](https://en.wikipedia.org/wiki/Subtitles#Subtitle_formats) of subtitle files. Currently we only accept `.srt` as the format of the subtitle.

# Screen Record
[喵影工厂](https://miao.wondershare.cn/filmora-video-editor-ad.html)

[OBS Studio](https://github.com/obsproject/obs-studio/)
