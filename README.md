# livestream-transition-grabber
Livestream transition frames grabber.

Image sequence to video
```
ffmpeg -r 100 -i %d.png -vcodec png -filter:v "setpts=1.2*PTS" transition.mov
```
