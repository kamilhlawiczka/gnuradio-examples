# Open GnuRadio

```
gnuradio-companion 02_base_play_from_file/play_from_file.grc
```
It is important to have good working directory. File will play from `01_base_record_from_mic/output.wav`


# Notice

Flow is from mic to wav file. When I was try play output wav file by mplayer, sound is interrupts. You can conver file to mp3 

```
ffmpeg -i output.wav output.mp3
mplayer output.mp3
```

or play by aplay:

```
aplay output.wav
```
