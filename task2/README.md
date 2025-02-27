# Fuel Oil Composition Calculator

This project is a web-based fuel oil composition calculator that calculates the elemental composition and lower heating value based on the given parameters of fuel oil.

## Features

- Calculates the composition of dry and combustible fuel mass from the given working mass composition.
- Computes lower heating value using specified formulas.
- User-friendly interface with input fields for fuel components and a calculate button.

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Use

1. Open `index.html` in a web browser.
2. Enter the values for the fuel components:
   - Carbon (C) in %
   - Hydrogen (H) in %
   - Oxygen (O) in %
   - Sulfur (S) in %
   - Lower heating value (Q) in МДж/кг
   - Moisture content (W) in %
   - Ash content (A) in %
   - Vanadium (V) in мг/кг
3. Click the "Calculate" button.
4. View the calculated values for combustible mass, lower heating value, and vanadium content.

## Formulae Used

- Combustible Mass: `Combustible Mass = 100 - W`
- Lower Heating Value (LHV):
  - `Lower Heating Value = Q * (1 - (W / 100))`
- Vanadium Content: `Vanadium Content = (V / 1000) * Combustible Mass`

## License

This project is open-source and available for modification and distribution.
