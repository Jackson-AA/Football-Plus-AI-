# Football Play Visualization

This project is a web-based visualization of football plays using HTML5 canvas and JavaScript. It allows users to view and interact with various football play formations and player movements.

## Features

- Visual representation of a football field with yard lines and hash marks
- Display of offensive and defensive player positions
- Visualization of player movement paths for offensive players
- Ability to play, pause, and reset the play visualization
- Support for using player sprites (optional)

## Getting Started

To run the project locally, follow these steps:

1. Clone the repository to your local machine:

2. Navigate to the project directory:

3. Open the `index.html` file in a web browser.

Alternatively, you can use a local development server like Live Server (Visual Studio Code extension) or serve the project with a simple HTTP server like Python's `http.server` or Node.js' `http-server`.

## Usage

1. Upon opening the `index.html` file, you will see a canvas representing the football field and three buttons: "Play", "Pause", and "Reset".

2. Click the "Play" button to start the play visualization. The offensive players will move along their predefined paths, and the defensive players will be displayed in their positions.

3. Click the "Pause" button to pause the play visualization at any time.

4. Click the "Reset" button to reset the play visualization to its initial state.

## Customization

You can customize various aspects of the play visualization by modifying the code in the `index.html` file:

1. **Play Data**: The offensive and defensive player positions, as well as the offensive player paths, are defined in the `playData` object. You can modify these values to create different play formations and movements.

2. **Player Sprites**: By default, the code uses simple circles to represent players. However, you can use player sprites by providing the appropriate image paths in the `playerSprites` object.

3. **Field Customization**: The `drawField` function is responsible for drawing the football field. You can modify this function to add or customize elements like yard lines, hash marks, or other field markings.

4. **Animation**: Currently, the code renders static frames of the play. You can implement animation by updating the player positions and paths based on a timer or using a library like GreenSock (GSAP) for smoother animations.

5. **Dynamic Play Generation**: The current implementation uses hardcoded play data. You can extend the project to generate plays dynamically based on user input or predefined rules.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
