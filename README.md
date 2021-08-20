# FFmpegColab
You need to prepend a `!` to execute a shell command in Goole Colab or Jupyter

```
!git clone https://github.com/puligclone/FFmpegColab.git
!cp -r ./FFmpegColab/bin/. /usr/bin/
!chmod +x /usr/bin/ffmpeg
!chmod +x /usr/bin/SvtAv1EncApp
!chmod +x /usr/bin/aomenc
```

Check the installed ffmpeg version
```!ffmpeg -version```

#Congratulations, ffmpeg with cuda support is installed!
