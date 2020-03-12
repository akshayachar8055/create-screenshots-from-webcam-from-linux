# :camera: SimpleCamera
Create screenshots from webcam on Linux

## :hammer_and_wrench: Compiling:
``` bash
git clone https://github.com/LimerBoy/SimpleCamera/
cd SimpleCamera/
g++ webcam.cpp -o webcam
```

## :gift: Usage:
``` bash
./webcam "delay" "device" "output"
./webcam 4500 /dev/video0 photo.jpg
```

## :pencil: Get cameras list:
``` bash
ls -l /dev/video*
```

## :hearts: Thanks:
Many thanks to [mike168m](https://github.com/mike168m) for his [program](https://gist.github.com/mike168m/6dd4eb42b2ec906e064d).
