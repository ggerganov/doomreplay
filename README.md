# doomreplay

Replay doom by providing keyboard input from a file and optionally storing the replay as a video file

## Build

```bash
cd doomgeneric
make -f Makefile.dr
```

## Input

```
,   - new frame
x   - escape
e   - enter
l   - left
r   - right
u   - up
d   - down
a   - alt
s   - shift
p   - use
f   - fire
t   - tab
0-9 - weapons
```

## Examples

```bash
./doomgeneric -iwad doom1.wad -input ../input/solve1.txt -nrecord 1200 -framerate 35 -render_frame -render_input -render_username -output replay.mp4
vlc replay.mp4
```
