# ACM CTF Bonus Key Webpage

## Overview

This repository contains a professional and visually appealing webpage designed to celebrate the discovery of a bonus key in the ACM CTF (Capture The Flag) Challenge. The webpage features a sleek, modern design with a dark theme, dynamic color effects, and subtle animations to create an engaging user experience. It includes a navigation menu and a submit button, consistent with the original ACM CTF Challenge interface, ensuring seamless integration into the broader CTF environment.

The webpage is built using HTML, CSS, and JavaScript, with a focus on clean code, responsiveness, and accessibility. It displays a congratulatory message, the bonus key (`BONUS_KEY{ACM_ULTIMATE_2025}`), and incorporates animations like drifting particles and glowing effects to enhance the visual appeal without overwhelming the user.

## Features

- **Professional Design**: A clean, dark-themed interface with a focus on readability and aesthetics.
- **Dynamic Animations**: Subtle particle and glow effects that add sophistication without clutter.
- **Responsive Layout**: Optimized for both desktop and mobile devices, ensuring a consistent experience.
- **Navigation Menu**: Includes a URL input and "Navigate" button for seamless integration with the ACM CTF environment.
- **Submit Button**: Links to an external form for flag submission, maintaining consistency with the original CTF challenge.
- **Dynamic Colors**: The key container features dynamic border color changes for visual interest.
- **Console Easter Egg**: Outputs the bonus key and a victory message in the console for CTF participants to discover.

## File Structure

- `congrats.html`: The main HTML file containing the webpage structure, styles, and JavaScript logic.
- No external dependencies are required, as all styling and functionality are self-contained.

## Setup and Installation

To run the webpage locally or deploy it, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/acm-ctf-bonus-key.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd acm-ctf-bonus-key
   ```

3. **Open the Webpage**:
   - Open `congrats.html` in a web browser (e.g., Chrome, Firefox) by double-clicking the file or using a local server.
   - Alternatively, serve the file using a simple HTTP server:
     ```bash
     python -m http.server 8000
     ```
     Then, navigate to `http://localhost:8000/congrats.html` in your browser.

## Usage

- **Navigation Menu**: Enter a URL in the input field and click "Navigate" to open it in a new tab. This feature mirrors the original ACM CTF interface.
- **Submit Flag**: Click the "Submit Flag" button to open the external form (https://forms.gle/GiDAHRV4reAjWK6x7) for submitting the bonus key.
- **Console Interaction**: Open the browser's developer console (F12 or right-click > Inspect > Console) to view the Easter egg message and the bonus key (`BONUS_KEY{ACM_ULTIMATE_2025}`).
- **Responsive Design**: The webpage adapts to different screen sizes, ensuring accessibility on mobile devices and desktops.

## Design Choices

- **Typography**: Uses the 'Inter' font for a modern, clean look suitable for a professional CTF environment.
- **Color Scheme**: A dark theme with indigo and purple accents (#4f46e5, #a855f7) for a cohesive and cyberpunk-inspired aesthetic.
- **Animations**: 
  - Drifting particles create a subtle background effect, enhancing depth without distraction.
  - Glowing effects on the key container provide a focal point and emphasize the bonus key.
  - Fade-in animations for text ensure a smooth and engaging user experience.
- **Performance**: Lightweight with no external dependencies, ensuring fast loading times.
- **Accessibility**: High-contrast text and a clear layout improve readability for all users.

## Development Notes

- **HTML Structure**: The webpage uses semantic HTML for better accessibility and maintainability.
- **CSS**: Leverages CSS animations and gradients for dynamic effects, with careful attention to avoiding visual clutter.
- **JavaScript**: Handles particle and glow animations, dynamic color changes, and navigation functionality. Includes error handling for robust user interaction.
- **Responsive Design**: Media queries ensure the layout adapts to smaller screens, adjusting font sizes, padding, and navigation layout.

## Contributing

Contributions are welcome! If you have suggestions for improving the design, animations, or functionality, please:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the ACM CTF Challenge, designed to provide a professional and engaging victory page for participants.
- Built with simplicity and performance in mind, ensuring a seamless experience for CTF enthusiasts.