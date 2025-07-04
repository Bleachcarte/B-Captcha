# B-Captcha
# B-Captcha (Bleach Captcha)

A lightweight, user-friendly moving-slot CAPTCHA replacement designed to enhance bot protection while providing a smooth, enjoyable user experience.

## Features

- Drag and drop shapes into moving slots to verify humanity
- Automatically switches to tap-to-place mode on touch devices
- Keyboard navigation for accessibility
- Screen reader support with ARIA labels
- Reduced motion mode for sensitive users
- Auto-verifies when all matches are complete
- Behavioral checks on drag duration and movement
- Honeypot field for invisible bot detection
- Time-based token validation
- Dynamic slot shuffling to prevent automation
- Decoy shapes to waste bot time
- Responsive design that adapts to all screen sizes
- Simple, clean UI with smooth animations
- No external dependencies - pure HTML, CSS, and JavaScript
- Multiple emoji theme sets (60+ combinations)
- Focus-time measurement to detect headless browsers

## Demo

Try the live demo [here](https://bleachcarte.github.io/B-Captcha/)

## Usage

1. Clone or download the repository
2. Open `index.html` in your browser
3. Match the emoji shapes to their slots using:
   - Drag-and-drop (desktop)
   - Tap-to-select (mobile)
   - Keyboard controls (accessibility)
4. System auto-verifies when all matches are correct

## Installation & Development

- Requires only a modern web browser
- No build step or dependencies
- Customize shapes, movement parameters, or UI styles in `index.html`

## Configuration

const SECURITY = {
  // Security Parameters
  maxAttempts: 3,           // Wrong tries before lockout
  lockoutTime: 10000,       // 10 second cooldown
  minDragTime: 150,         // Minimum drag duration (ms)
  maxDragTime: 15000,       // Maximum drag duration (ms)
  minSolveTime: 2000,       // Minimum verification time (ms)
  
  // Display Parameters
  successDisplayTime: 1500, // Success message display duration (ms)
  
  // Redirection
  successRedirectURL: "success.html" // Change this to any post-verification URL
  // Example alternatives:
  // successRedirectURL: "https://yourdomain.com/welcome"
  // successRedirectURL: "/dashboard.html"
};
## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## License

MIT License © 2025 Daniel Ekong

---

*Built with Swag by Daniel (Bleach) Ekong*
