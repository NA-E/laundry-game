# 🧺 Laundry Game for Toddlers

A simple, gentle laundry game designed for young children (ages 3+). The game features a calm, muted color palette with no bright lights or sounds, making it perfect for extended play without overwhelming little ones.

## Features

- **Touch-based gameplay**: Simply drag clothes from the basket to the washing machine
- **Calm design**: Muted, pastel colors (soft blues, greens, pinks, browns) instead of bright colors
- **No audio**: Completely silent gameplay
- **Haptic feedback**: Optional vibration feedback for interactions (can be toggled on/off)
- **Simple animations**: Smooth spinning washing machine to show clothes being washed
- **Auto-play**: Game automatically resets after each wash cycle
- **Mobile-friendly**: Fully responsive design optimized for touchscreen devices

## How to Play

1. **Start the game**: Open `index.html` in a web browser
2. **Drag clothes**: Touch and drag clothing items from the basket to the washing machine
3. **Full load**: Once all clothes are in the machine, it automatically starts washing
4. **Reset**: Tap "New Game" to start over at any time
5. **Toggle haptic**: Use "Haptic: ON/OFF" button to enable/disable vibration feedback

## How to Use on Mobile

### Option 1: Local File
1. Download or copy the game files to your phone
2. Open `index.html` directly in your mobile browser
3. Bookmark it for quick access

### Option 2: Web Server
1. Upload the `index.html` file to any web hosting service
2. Access via the web URL on your phone's browser
3. Add to home screen for app-like experience

### Option 3: Local Development Server
If you have Python installed:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Then visit `http://localhost:8000` on your phone

Or with Node.js:
```bash
npx http-server
```

## Tips for Best Experience

- **Full screen**: Open in full-screen mode for better touch interaction
- **Landscape or Portrait**: Works great in both orientations
- **Haptic feedback**: Great for positive reinforcement - turn on for interactive play, off for calm downtime
- **Large touch targets**: All interactive elements are sized generously for small fingers
- **Low brightness**: Muted background colors reduce eye strain during extended play

## Technical Details

- **Pure HTML5**: No external dependencies needed
- **Responsive**: Adapts to any screen size
- **Touch optimized**: Handles both mouse and touch events
- **Lightweight**: Single file, fast loading

## Browser Support

Works on all modern browsers including:
- Chrome/Chromium
- Safari (iOS)
- Firefox
- Edge

## Haptic Feedback

The game uses the Vibration API for haptic feedback:
- Grab cloth: 50ms vibration
- Drop in machine: 100ms vibration
- Start washing: 150ms vibration
- Finish washing: Two 100ms vibrations

Haptic works on most modern Android devices and some iPhones (iOS 13+).

## Color Palette

The game uses calming, muted colors:
- **Background**: Soft beige/cream tones
- **Basket**: Warm brown
- **Machine**: Soft gray/beige
- **Clothes**: Pastel red, blue, yellow, green, pink
- **Text**: Muted brown (not black, for reduced contrast)

## Development Notes

All game logic is contained in a single HTML file for easy deployment and modification. Feel free to customize:
- Number of clothes items
- Clothing colors and emojis
- Washing animation duration
- Haptic vibration patterns

Enjoy! 🧺✨
