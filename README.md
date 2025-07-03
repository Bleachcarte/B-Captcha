# B-Captcha
# B-Captcha (Bleach Captcha)

A lightweight, user-friendly moving-slot CAPTCHA replacement designed to enhance bot protection while providing a smooth, enjoyable user experience.

## Features

- Drag and drop shapes into moving slots to verify humanity  
- Automatically switches to tap-to-place mode on devices or browsers without reliable drag-and-drop support  
- Slots move smoothly with responsive bouncing within the container  
- Behavioral checks on drag duration and movement to detect bots  
- Honeypot field for invisible bot detection  
- Responsive design that adapts to different screen sizes and devices  
- Simple, clean UI with smooth animations and rounded elements  
- No external dependencies; pure HTML, CSS, and JavaScript  

## Demo

Try the live demo [here](https://bleachcarte.github.io/B-Captcha/)  

## Usage

1. Clone or download the repository  
2. Open `index.html` in your browser or serve with Live Server  
3. Follow the on-screen instructions:  
   - On devices with drag-and-drop support: hold and drag each shape into its matching moving slot  
   - On devices without drag-and-drop support: tap a shape to select it, then tap the matching moving slot to place it  
4. Click "Verify" once all shapes are correctly matched  

## Installation & Development

- Requires only a modern web browser  
- Optional: Use VSCode Live Server for local testing  
- Customize shapes, movement parameters, or UI styles in `index.html`

## Configuration

You can tweak parameters inside the script section, such as:

- Slot movement amplitude and frequency  
- Drag behavior thresholds (duration, distance)  
- Number of allowed fails and cooldown time  

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## License

MIT License © 2025 Daniel Ekong

---

*Built with Swag by Daniel (Bleach) Ekong*
