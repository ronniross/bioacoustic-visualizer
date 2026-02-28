# bioacoustic-visualizer

A collection of Python-based scripts designed to transform audio recordings into visual representations (MP4/GIF), through digital signal processing techniques.

## Visualizer 1

### α 3D peak frequency per frame

Generates animated 3D pitch trajectories from bioacoustic signals. This script calculates STFT, extracts peak frequency/amplitude data over time, and renders a smooth, rotating 3D animation with live frequency tracking. northern-waterthrush-render:

<p align="center">
  <img src="https://github.com/ronniross/bioacoustic-visualizer/blob/main/renders/northern-waterthrush-3.gif" alt="visualizer" width="500"/>
</p>

[folder](https://github.com/ronniross/bioacoustic-visualizer/tree/main/%CE%B1-3D-peak-frequency-per-frame)

## Visualizer 2 

### β radial mapping deep dea echolocation sonar visualizer

Instead of a 3D spiral, this script maps time to a circle (like a radar sweep). The amplitude of the clicks violently spikes outward from the baseline, and the frequencies dictate the color of the bioluminescent "bursts." As the audio plays, a radar playhead sweeps around the circle, leaving a glowing trail behind it, with dynamic typography in the center. sperm-whale-render:

<p align="center">
<img src="https://github.com/ronniross/bioacoustic-visualizer/blob/main/renders/sperm-whale-sonar-echolocation-2.gif" alt="visualizer" width="500"/>
</p>

[folder](https://github.com/ronniross/bioacoustic-visualizer/tree/main/%CE%B2-sonar-echolocation-radial)

---

Ronni Ross  
2026
