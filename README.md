# quad-interactive-fader

Quad Interactive Mix Fader - An interactive web audio mixer with real-time crossfading.

## Project Structure

```
quad-interactive-fader/
├── index.html              # Main application file
├── package.json            # Node.js dependencies and scripts
├── assets/
│   ├── audio/             # Audio files (.wav)
│   │   ├── QUAD_VOCALS_BEAT.wav
│   │   ├── QUAD_VOCALS.wav
│   │   ├── RAW_VOCALS_BEAT.wav
│   │   └── RAW_VOCALS.wav
│   └── fonts/             # Font files
│       └── VCR_OSD_MONO_1.001.ttf
├── docs/                  # Documentation
├── src/                   # Source files (for future use)
├── styles/                # Stylesheets (for future use)
├── utils/                 # Utility scripts (for future use)
└── visualizer/            # Visualizer components (for future use)
```

## Setup & Running

### Prerequisites
- Node.js (v14 or higher) and npm

### Installation

1. Install dependencies:
```bash
npm install
```

### Running the Local Server

Start the development server:
```bash
npm start
```

Or start with auto-open in browser:
```bash
npm run dev
```

The server will start on `http://localhost:8080`

### Alternative: Python Server

If you don't have Node.js, you can use Python's built-in server:

```bash
# Python 3
python3 -m http.server 8080

# Python 2
python -m SimpleHTTPServer 8080
```

Then open `http://localhost:8080` in your browser.

## Features

- Interactive dual-slider audio mixer
- Real-time crossfading between raw/processed vocals and vocals/beat
- Slingshot mechanics for quick slider navigation
- Visual effects and particle animations
- Easter egg unlockable content