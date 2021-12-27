# [Color Grading Made EASY | Davinci Resolve 17 Tutorial](https://www.youtube.com/watch?v=iSAUD0I9pXI)

# Live grading and monitoring
## Hardware setup
**Gear**
- BMPCC 4K camera, BM UltraStudio Recorder 3G, HDMI Cable
- Gray/Focus screen and stand
- Key Light, Fill light, practical lights
- Iphone with BMPCC app

1. Connect camera to tripod, HDMI cable to Recorder 3G, thunderbolt cable to MBP
2. Test with OBS app

**Camera Settings**
- Record tab
  - Dynamic Range: Film (Log).
  - Sensor area: 4K
  - Project Frame rate: 60fps
  - Off speed recording: Off
  - Off speed frame rate: grayed out
  - Prefered card for recording: External drive
  - Stop rec if card drops frame: on
- Monitor tab
  - HDMI and LCD:  everything off except false color.  (toggle this off when you have a good exposure)


## Software setup
1. Open Da Vinci Resolve and create a new project
2. `Shft 9` for Project settings -> set timeline frame rate and playback framerate to match frame rate of camera (60fps)
3. Go to color tab and press `cmd R` to turn on live.  Should see live feed
4. Click on effects tab at top right of color menu
5. `alt s` to make another node
6. Search for *false color* and drag to node
7. Adjust iso/shutter/iris for correct exposure.
8. Acquire

---

