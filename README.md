# Necromunda Rolls

![Necromunda Rolls Logo](https://i.imgur.com/ustpoBI.gif)

## Overview

**Necromunda Rolls** is a web-based dice rolling tool designed for players of the tabletop miniature game *Necromunda*. It simplifies the process of rolling various types of dice used in the game and provides a user-friendly interface to select the number of dice to roll, visualize the results with animated dices and apply special rules like 2d6 Lasting Injuries.

[USE IT NOW!](https://erdemdur.github.io/necromunda-rolls/)

## Features
- **Multiple Dice Types**: Roll Scatter, Ammo/Rapid Fire, Injury, Damage, Vehicle Location, Control and standard D6 dice.
- **Visual Feedback**: Displays rolled dice with random rotations on a canvas.
- **Customizable Settings**: Hide specific dice types, adjust text size and toggle sound effects.
- **Responsive Design**: Works on both desktop and mobile devices with adaptive layouts.
- **Local Storage**: Remembers user preferences like hidden dice types and text size.

## How It Works
1. **Select Dice**: Use the +/- buttons or input fields to choose the number of dice for each type.
2. **Roll Dice**: Click the "Roll" button to generate random results, displayed both as text and visually on the canvas.
3. **Clear Results**: Use the "Clear" button for individual dice types or "Clear All" to reset everything.
4. **Settings**: Access the settings menu (via the gear icon) to customize the tool:
   - Hide unused dice types.
   - Switch between small and big text sizes.
   - Toggle the roll sound (muted by default, can be turned on).
5. **Special Rules**: Automatically applies rules like 2d6 Lasting Injuries when two D6 dice are rolled alone.

## Setup and Usage
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/erdemdur/necromunda-rolls.git
   cd necromunda-rolls
   ```
2. **Open the File**: Simply open `index.html` in a web browser to start using the tool. No server is required as it runs locally.
3. **Add Audio (Optional)**: Place your own `roll.mp3` audio file in the same directory as `index.html` and update the audio path in the JavaScript code (see below for instructions).
4. **Customize**: Modify the HTML, CSS, or JavaScript files to suit your needs or contribute improvements via pull requests.

## Contributing
Contributions are welcome! Please follow these steps:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Submit a pull request with a clear description of your changes.

## License
This project is open-source under the [MIT License](LICENSE). Feel free to use, modify, and distribute it.

## Contact
For questions or feedback, please open an issue on the [GitHub repository](https://github.com/erdemdur/necromunda-rolls) or contact the maintainer.

## Acknowledgements
- Dice images and game data inspired by *Necromunda* by Games Workshop.
- Built with HTML, CSS and JavaScript.
