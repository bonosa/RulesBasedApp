# 🎵 Simple Noise Filter - README

## What This Does
• **Listens to your environment** through your microphone
• **Identifies noise types** like traffic, conversation, construction, or quiet
• **Recommends soundscapes** to help mask the noise
• **Plays relaxing sounds** (rain, ocean, forest, café, white noise) on a timer
• **Automatically stops** when the timer runs out

## How It Works
• **Audio Analysis**: Uses frequency analysis to identify different types of environmental noise
• **Pattern Recognition**: Analyzes low, mid, and high frequency patterns to classify sounds
• **Confidence Rating**: Shows how certain the system is about the noise type detected
• **Sound Recommendations**: Suggests the best soundscape based on the type of noise detected

## What You Need
• **Web browser** (Chrome, Firefox, Safari, Edge)
• **Microphone access** (the browser will ask for permission)
• **HTTPS website** (microphone only works on secure sites)
• **Your MP3 files** in a folder called `sounds/`

## File Setup
Create a folder called `sounds/` and put these MP3 files in it:
• `rain.mp3` - Rain sounds
• `ocean.mp3` - Ocean waves
• `forest.mp3` - Forest/nature sounds
• `cafe.mp3` - Café ambiance
• `white-noise.mp3` - White noise

## How to Use
1. **Click "Start Analyzing"** - Allow microphone access when asked
2. **Watch the detection** - See what type of noise is detected with confidence level
3. **Check recommendations** - See which soundscape is suggested for your environment
4. **Choose a sound** - Click any of the 5 sound buttons to start playing
5. **Set timer** - Use +/- buttons to adjust how long sounds play (default: 1 hour)
6. **Relax** - Sounds loop automatically and stop when timer ends

## Noise Types Detected
• **Quiet** - Very low background noise
• **Traffic** - Low rumbling sounds from vehicles
• **Conversation** - Human speech and talking
• **Construction** - Loud, irregular building/repair noises
• **General** - Mixed or unidentified environmental sounds

## Sound Recommendations
• **Traffic noise** → Ocean or White Noise (masks low frequencies)
• **Conversation** → White Noise or Café (masks speech)
• **Construction** → Rain or Forest (masks sharp sounds)
• **Quiet environment** → Any sound for focus/relaxation

## Timer Controls
• **Default**: 60 minutes
• **Adjust**: -15min, -5min, +5min, +15min buttons
• **Reset**: Returns to 60 minutes
• **Auto-stop**: Sounds automatically stop when timer reaches zero

## Technical Notes
• **Frequency Analysis**: Examines audio spectrum from 0Hz to ~20kHz
• **Real-time Processing**: Updates noise detection several times per second
• **Browser-based**: No data sent to external servers - everything runs locally

## Troubleshooting
• **Button turns red but doesn't work**: Make sure you're on HTTPS and allow microphone access
• **No sound plays**: Check that MP3 files are in the `sounds/` folder with correct names
• **Detection not working**: Ensure microphone isn't muted and has permission
• **Timer not starting**: Click a sound button first, then timer begins

## Privacy
• **No recording**: Audio is analyzed in real-time, never stored
• **No internet required**: All processing happens in your browser
• **No data collection**: Nothing is sent to external servers

## Browser Compatibility
• ✅ **Chrome** (recommended)
• ✅ **Firefox**
• ✅ **Safari**
• ✅ **Edge**
• ❌ **Internet Explorer** (not supported)

## File Structure
```
your-website/
├── index.html (the main noise filter file)
└── sounds/
    ├── rain.mp3
    ├── ocean.mp3
    ├── forest.mp3
    ├── cafe.mp3
    └── white-noise.mp3
```
