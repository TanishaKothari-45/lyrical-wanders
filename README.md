# Lyrical Wanders - Chaos Visualizer

An advanced, immersive audio visualizer that creates dynamic, wave-based visualizations from your music. The visualizer transforms audio data into mesmerizing visual patterns with fluid wave motions, particle explosions, and dynamic color responses.

![Chaos Visualizer Demo](demo.gif)

## Features

- **Immersive Wave Simulations**: Particles move in cohesive wave formations with multiple overlapping wave systems
- **Dynamic Sphere Deformation**: Inner sphere transforms with complex wave patterns that respond to audio
- **Audio-Reactive Particle Systems**: Over 5,000 particles respond to music with different behaviors:
  - Vortex-influenced spirals
  - Multi-directional wave systems
  - Dynamic orbital systems
- **Real-time Audio Analysis**: Analyzes frequency bands (bass, mids, treble) and detects beats
- **Interactive Audio Filter**: Modify your music with adjustable filter types (lowpass, highpass, bandpass) with frequency and resonance controls
- **Post-Processing Effects**: Bloom effect enhances visual appeal with audio-responsive glow
- **Camera Movement**: Dynamic camera responds to music for immersive viewing experience
- **Video Recording**: Capture 10-second WebM videos of your visualizations with synchronized audio for sharing
- **Highly Customizable**: Fine-tuned parameters for different music styles

## Getting Started

### Prerequisites

A modern web browser with WebGL and Web Audio API support.

### Running Locally

1. Clone this repository
```bash
git clone git remote add origin https://github.com/TanishaKothari-45/lyrical-wanders.git
cd lyrical-wonders
```

2. Launch with Live Server
   - If using VS Code: Install the "Live Server" extension, then right-click on `chaos-visualizer/index-tone.html` and select "Open with Live Server"
   - If using another editor: Use your preferred local development server

3. The visualizer should automatically open in your default browser

## Usage

1. Click the "Choose Audio File" button to choose a music file
2. Adjust the volume using the slider
3. Hit "Play" button to see our visualiser making effect
4. Try different filter settings to alter the audio:
   - **Filter Type**: Select between lowpass, highpass, bandpass, or none
   - **Frequency**: Adjust the cutoff frequency
   - **Resonance**: Control the resonance/Q of the filter
   - **Automation**: Enable automatic filter sweeping
5. Record your visualization:
   - Click the red "Record" button in the bottom-right corner
   - The visualizer will record for 10 seconds with a countdown
   - After recording completes, the video will automatically download with a timestamp in the filename
   - Share your creation on social media platforms like Twitter/X or LinkedIn

## Technologies Used

- [Three.js](https://threejs.org/) - WebGL-based 3D graphics library
- [Tone.js](https://tonejs.github.io/) - Web Audio framework for audio processing
- Web APIs:
  - Canvas API with captureStream() for WebGL recording
  - MediaRecorder API for video capture
  - MediaStream API for audio/video stream handling
- HTML5/CSS3/JavaScript - Core web technologies

## Performance Tips

- For optimal performance, close unnecessary browser tabs and applications
- Reduce particle count in settings if experiencing lag on older hardware
- Best experienced on a computer with dedicated graphics
- Video recording requires additional system resources - if you experience performance issues during recording, try closing other applications

## Future Enhancements

- VR support for immersive audio-visual experience
- Additional visual presets for different music genres
- Audio input from microphone for live performance visualization
- Beat mapping for synchronized visual events
- Extended recording options with different quality settings and durations

## License

This project is released under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by music visualizers from Winamp, iTunes, and Windows Media Player
- Thanks to the Three.js and Tone.js communities for their excellent documentation and examples 