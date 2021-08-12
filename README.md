# iPhone RGBD Recorder

## Environment

### Hardware

  * iPhone 12 Pro/Pro Max
  * Windows PC

### Software

   * Windows 10
   * Python 3.8.10
   * opencv-python 4.5.3.56
   * record3d 1.3.0

## Install

### iPhone

* Install the Record3D app from the App Store.

    https://apps.apple.com/jp/app/record3d-3d-videos/id1477716895

### PC

* Install Python

    https://www.python.org/downloads/windows/

* Git Clone and Install Package

```bash
git clone https://github.com/ylabo0717/iPhone-RGBD-Recorder.git
cd iPhone-RGBD-Recorder
pipenv sync
pipenv shell
```

## Usage

### iPhone

1. Connect your iPhone to your PC via USB.

2. Launch the Record3D app on your iPhone.

    <img src="images/Record3D_001.png" width="256">

3. Change Record3D Settings

    <img src="images/Record3D_002.png" width="256">

| item  |  value  |
| :-: | :-: |
| Live RGBD Video Streaming  | USB |
| Higher quality LiDAR recording  | ON (Optional) |


4. Start Recording

    <img src="images/Record3D_003.png" width="256">

### PC

5. Execute Recoder on your PC.

```bash
python iphone_rgbd_recorder.py
```

6. Press the 'r' key in the RGBD Viewer window to start recording.


