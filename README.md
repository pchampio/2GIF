# FFmpeg gif wrapper

#### A simple command, used to convert videos to gif.
![Saber](exemple/saber.gif)

### Usage:

```
$ 2gif --help
Usage: 2gif [options] <input video file> <output gif name>

Options:
  -h, --help            Show this help
  -r, --resolution      Set the pixels wide (preserving the aspect ratio)
  -f, --fps             Set the gif frame rate
                          default 12
  -s, --start           Skip the first x seconds
  -t, --to              Capture to x seconds
  -d, --duration        Set the duration
  -l, --loop            Number of times to loop the output
                          default: no loop
                          -l      output loop infinitely
                          -l10    output loop 10 times
Examples:
  2gif input.mp4 out.gif
  2gif input.mp4 out.gif -s00:01 -d5 -r450
  2gif input.mp4 out.gif -s20:00 -d5 -l --fps30
```

### Installation:

```
sudo curl -L https://raw.githubusercontent.com/Drakirus/2GIF/master/2gif -o /bin/2gif && sudo chmod 755 /bin/2gif
```
