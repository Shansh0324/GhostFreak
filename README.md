# GhostFreak

An AI-powered assistant application built with Electron that provides real-time assistance during interviews, sales calls, and other scenarios using Google's Gemini AI.

## Features

- **Real-time AI Assistance**: Get instant, ready-to-speak responses during conversations
- **Audio Capture**: Captures system audio for transcription and analysis
- **Multiple Profiles**: Pre-configured profiles for interviews, sales calls, and more
- **Customizable**: Adjust layout, language, screenshot intervals, and image quality
- **Cross-platform**: Works on Windows, macOS, and Linux

## Requirements

- Node.js (v14 or higher)
- Google Gemini API key

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd ghostfreak
```

2. Install dependencies:
```bash
npm install
```

## Usage

1. Start the application:
```bash
npm start
```

2. Enter your Google Gemini API key in the main view
3. Select your preferred profile (interview, sales, etc.)
4. Configure settings as needed
5. Click "Start" to begin capturing audio and receiving AI assistance

## Building

Package the application:
```bash
npm run package
```

Create distributables:
```bash
npm run make
```

## Testing

Run tests:
```bash
npm test
```

## Project Structure

```
ghostfreak/
├── src/
│   ├── components/        # UI components
│   ├── utils/             # Utility functions
│   ├── assets/            # Static assets
│   ├── index.js           # Main Electron process
│   └── preload.js         # Preload script
├── package.json
└── README.md
```

## Configuration

Configuration files are stored in platform-specific locations:
- **Windows**: `%APPDATA%\ghostfreak-config`
- **macOS**: `~/Library/Application Support/ghostfreak-config`
- **Linux**: `~/.config/ghostfreak-config`



