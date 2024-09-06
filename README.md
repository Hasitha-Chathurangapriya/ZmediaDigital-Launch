# Z Media Digital Launch

This project is a landing page for the launch of Z Media Digital. It includes a countdown, animation effects, and sound effects to create an engaging experience.

## Features

- **Countdown Timer**: Displays a countdown from 3 seconds before redirecting to the Z Media Digital website.
- **Animations**: Utilizes GSAP for animations and Canvas Confetti for a celebratory effect.
- **Sound Effects**: Plays a sound effect upon launch using Howler.js.
- **Space Key Activation**: Allows triggering the launch animation by pressing the Space key.

## Technologies Used

- **HTML**: Structure of the page.
- **CSS**: Styling (referenced in `style.css`).
- **JavaScript**: Handles animations and functionality.
  - **GSAP**: For smooth animations.
  - **Canvas Confetti**: For fullscreen confetti effect.
  - **Howler.js**: For playing sound effects.

## How to Use

1. **Setup**: Ensure you have the following files in your project directory:
   - `index.html`: The main HTML file.
   - `style.css`: The CSS file for styling.
   - `path/to/launch-sound.mp3`: The sound effect file (replace with your actual file path).

2. **Include Libraries**: The project uses external libraries loaded via CDN:
   - GSAP: [cdnjs](https://cdnjs.cloudflare.com/ajax/libs/gsap/3.11.1/gsap.min.js)
   - Canvas Confetti: [jsDelivr](https://cdn.jsdelivr.net/npm/canvas-confetti@1.5.1/dist/confetti.browser.min.js)
   - Howler.js: [cdnjs](https://cdnjs.cloudflare.com/ajax/libs/howler/2.2.3/howler.min.js)

3. **Launch the Page**:
   - Open `index.html` in a web browser.
   - Click the "Launch Zmediadigital.com" button or press the Space key to trigger the launch animation.
   - The Space key provides an alternative way to activate the launch animation, enhancing user accessibility.

## Customization

- **Sound Effect**: Replace the `src` attribute in the `Howl` instance with the path to your sound effect file.
- **Styling**: Customize the appearance by editing `style.css`.

---

Happy launching!
