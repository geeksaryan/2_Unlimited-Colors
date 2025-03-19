# UnlimitedColors

UnlimitedColors is a fun and interactive JavaScript project that dynamically changes the background color of a webpage to random colors. Users can start and stop the color-changing effect with the click of a button.

## Features

- **Random Color Generator**: Generates random hex color codes for a vibrant and dynamic background.
- **Start/Stop Functionality**: Users can control the color-changing effect with dedicated buttons.
- **Real-Time Updates**: The background color changes every 250 milliseconds when the effect is active.
- **Console Logging**: Logs the generated color codes to the console for debugging or reference.

## How It Works

1. The `randomColor` function generates a random hex color code.
2. The `startChangingColor` function starts an interval that updates the background color every 250 milliseconds.
3. The `stopChangingColor` function stops the interval, halting the color-changing effect.
4. Buttons on the webpage trigger these functions using JavaScript event listeners.

## Project Structure

The project consists of the following files:

1. **`index.html`**: The main HTML file that contains the structure of the webpage.
2. **`style.css`**: The CSS file that styles the webpage, including button designs and responsive layout.
3. **`script.js`**: The JavaScript file that handles the button click events and changes the background color dynamically.
4. **`readme.md`**: This file, which provides an overview of the project.

## How to Run the Project

1. Clone or download the project files to your local machine.
2. Open the `index.html` file in any modern web browser.
3. Click the "Start" button to begin changing the background color.
4. Click the "Stop" button to halt the color-changing effect.

## Technologies Used

- **HTML**: For structuring the webpage.
- **CSS**: For styling the webpage.
- **JavaScript**: For generating random colors and handling user interactions.

## Example Output

When the "Start" button is clicked, the background color of the webpage changes to random colors every 250 milliseconds. The generated color codes are also logged in the browser console.

## Screenshot

![Screenshot](assets/Screenshot.png)

## Author

This project was created by **Aryan Raj**. Feel free to contribute or suggest improvements!

## License

This project is open-source and available for personal or educational use.


