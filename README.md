# Backshot Roulette Calculator

A web-based calculator utility designed for the game **Buckshot Roulette**. This tool helps you keep track of the remaining live and blank shells, calculates the odds in real-time, and visualizes the current shell lineup.

## Features

- **Shell Tracking**: Keep count of how many live and blank shells remain in the shotgun.
- **Odds Calculation**: Automatically calculates the probability of the next shell being live or blank based on current knowledge and remaining shells.
- **Knowledge Input**: Input known positions of shells (e.g., when using the Magnifying Glass item in-game) to deduce the remaining unknowns.
- **Lineup Visualization**: Visually display the current lineup of known, unknown, live, and blank shells to make strategic decisions.

## How to Use

1. Enter the starting number of **Live shells** and **Blank shells** for the current round.
2. Click **Populate Lineup** to set up the initial unknown sequence.
3. Whenever a shell is fired or cycled:
   - Click **Fire (Live)** if a live shell was discharged.
   - Click **Cycle (Blank)** if a blank shell was cycled.
4. If you discover the type of a shell at a specific position (using in-game items):
   - Enter the position number.
   - Select the type (LIVE or BLANK).
   - Click **Add Knowledge**.
5. The calculator will dynamically update the odds and deduce remaining shells if all of one type are accounted for.

## Technology Stack

- **HTML5** for layout and structure
- **CSS3** for modern, responsive styling
- **Vanilla JavaScript** for core logic, probability calculation, and DOM manipulation

## Running Locally

To run the calculator locally, simply clone or download the repository and open the `index.html` file in your preferred web browser. No build steps, dependencies, or local server are required.
