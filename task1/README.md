# Fuel Composition Calculator

    This project is a web-based fuel composition calculator that calculates the composition of dry and combustible
    fuel mass as well as the lower heating value based on the given elemental composition of the fuel.

## Features

- Calculates dry and combustible mass composition from given working mass composition.
- Computes lower heating value using Mendeléev’s formula.
- Simple user interface with input fields and a calculate button.

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Use

1. Open index.html in a web browser.
2. Enter the values for fuel components (HP, CP, SP, NP, OP, WP, AP) in percentage.
3. Click the "Calculate" button.
4. View the calculated dry mass composition, combustible mass composition, and lower heating value.

## Formulae Used

- Dry Mass Conversion Factor: KRS = 100 / (100 - WP)
- Combustible Mass Conversion Factor: KRG = 100 / (100 - WP - AP)
- Lower Heating Value (LHV):
  - QrH = 339 _ CP + 1030 _ HP - 108.8 _ (OP - SP) - 25 _ WP

## License

    This project is open-source and available for modification and distribution.
