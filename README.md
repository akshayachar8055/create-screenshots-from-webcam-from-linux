# :camera: SimpleCamera
Create screenshots from webcam on Linux

# :hammer_and_wrench: Compiling:
``` bash
git clone https://github.com/LimerBoy/SimpleCamera/
cd SimpleCamera/
g++ webcam.cpp -o webcam
```

# :gift: Usage:
``` bash
./webcam "delay" "device" "output"
./webcam 4500 /dev/video0 photo.jpg
```

# :pencil: Get cameras list:
``` bash
ls -l /dev/video*
```
