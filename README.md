# OSU! Joystick Trainer

A web-based joystick training game inspired by OSU! - the popular rhythm game. Practice precision control with your controller's analog sticks by hitting circles that appear on screen, just like OSU!

## Features

- **OSU-Style Gameplay**: Hit circles appear with shrinking approach circles, just like OSU!
- **Dual Joystick Training**: Use either left or right joystick to hit circles - whichever is closer!
- **Timing-Based Scoring**: Score 300, 100, 50, or Miss based on timing and accuracy
- **Combo System**: Build combos for higher scores
- **Difficulty Levels**: Easy, Normal, and Hard modes with different approach times and spawn rates
- **Real-time Statistics**: Track score, combo, accuracy, and hit counts
- **Visual Feedback**: Large score displays and combo counter
- Works with any controller supported by the Web Gamepad API

## Requirements

- A modern web browser (Chrome, Firefox, Edge, Safari)
- A gaming controller connected via USB or Bluetooth

## How to Play

1. Connect your gaming controller (DualSense, Xbox controller, etc.) to your computer
2. Open `index.html` in your web browser
3. Press any button on your controller to activate it
4. Click **"Start Game"** to begin
5. **Hit circles appear** on screen (can appear anywhere reachable by your joysticks)
6. **Move either joystick** to position the indicator over the circle (use whichever is closer!)
7. **Hit when the approach circle** (white outer circle) shrinks to match the hit circle size
8. **Score points** based on timing:
   - **300**: Perfect timing (within 50ms)
   - **100**: Good timing (within 100ms)
   - **50**: OK timing (within 150ms)
   - **Miss**: Too early, too late, or wrong position

## Controls

- **Start Game**: Begin a new game session
- **Pause**: Pause/resume the game
- **Reset**: Reset all statistics and start over
- **Difficulty**: Switch between Easy, Normal, and Hard

## Difficulty Levels

- **Easy**: 2 second approach time, 1.5 second spawn interval, larger tolerance
- **Normal**: 1.5 second approach time, 1 second spawn interval, medium tolerance
- **Hard**: 1 second approach time, 0.7 second spawn interval, tight tolerance

## Scoring

- Score = (300 hits × 300) + (100 hits × 100) + (50 hits × 50)
- Accuracy = (Total score / (Total hits × 300)) × 100%
- Combo increases with consecutive hits, resets on miss
- Max Combo tracks your best combo streak

## Tips

- Watch the approach circle - hit when it matches the hit circle size
- Position your joystick accurately before the timing window
- Practice smooth, controlled movements
- Start with Easy difficulty to learn the mechanics
- Build muscle memory for different joystick positions

## Controller Support

The program works with any controller that supports the Web Gamepad API, including:
- Sony DualSense (PS5)
- Sony DualShock 4 (PS4)
- Xbox controllers
- Generic USB controllers

## Browser Compatibility

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support (macOS 10.15+)

## Troubleshooting

- If no controller is detected, make sure it's properly connected and recognized by your operating system
- Press any button on the controller after connecting - some browsers require user interaction to access gamepad input
- For Bluetooth controllers, ensure they're properly paired with your device
- If circles aren't appearing, make sure you clicked "Start Game"

