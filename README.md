# ⛽ RaceTechAssistant

A lightweight engineering tool for sim racers to calculate fuel strategy and tyre pressure adjustments.

## Features

### Fuel Calculator
- **Normal Mode**: Basic race time and consumption calculations.
- **Pro Mode**: Adds tank capacity, formation/cool-down laps, mandatory pitstops, and detailed pitstop scheduling.
- **Safety Margin**: Customizable fuel buffer percentage.

### Tyre Pressures
- **Temperature Compensation**: Calculates pressure delta based on ambient temperature shifts (0.1 psi / °C).
- **Brake Duct Scaling**: Estimates pressure changes based on brake duct settings (0.2 psi / step).
- **Target Tracking**: Visual indicators for staying within defined pressure windows.

## Tech Stack
- **Frontend**: HTML5, Vanilla JavaScript, CSS3 (Bootstrap 5.3).
- **Storage**: `SessionStorage` for input persistence.
- **Design**: Responsive layout for mobile and desktop use.

## Usage
1. Clone the repository.
2. Open `index.html` in any web browser.

## Disclaimer
Calculations are estimates based on standard physics models. Results may vary by simulator and conditions. Validate with a test stint before competitive use.
