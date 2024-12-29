# Age_Calculator
## Learning Basic Web Development
## Watch it in [Action](https://praful-dev.github.io/Age_Calculator/) :- https://praful-dev.github.io/Age_Calculator/

A simple web-based age calculator that allows users to input their birthdate and calculates their exact age in years, months, and days.

## Features

- User-friendly interface for selecting a date of birth.
- Displays the exact age (years, months, days) below the input field.
- Handles invalid inputs gracefully.
- Styled with a clean and responsive design.

## Project Structure
├── index.html                                             
├── style.css                                              
└── README.md


## Usage

1. Clone or download the repository.
2. Open the `index.html` file in any modern web browser.
3. Select your birthdate using the date picker.
4. Click on the **Calculate** button to see your age displayed below.

## Code Explanation

### HTML
The main structure of the project is defined in the `index.html` file. It includes:
- A container for the input field and button.
- A `div` element to display the calculated result.

### JavaScript
The functionality is powered by a simple script embedded in the HTML:
- Retrieves the user's selected date.
- Validates the input to ensure a valid date is selected.
- Performs the calculation to determine the years, months, and days between the selected date and today.
- Displays the result dynamically in the result container.

### CSS
The `style.css` file (if applicable) provides styling for:
- The card layout and design.
- Button and input field aesthetics.
- Responsiveness for various screen sizes.

## Example Output

- If the user inputs `2002-06-06` and today's date is `2024-12-29`, the output will be: You are 22 years, 06 months, and 23 days old.


## Requirements

- A modern web browser that supports HTML5, CSS3, and JavaScript.
- No additional dependencies are required.

## How It Works

1. **Date Input**: The user selects their birthdate using the input field of type `date`.
2. **Calculate Age**: Upon clicking the button, the script computes the age:
 - Calculates the difference in years, months, and days.
 - Handles cases where the current day or month is earlier than the birth day or month.
3. **Display Result**: The calculated age is displayed in the designated result area.

## Contributing

Feel free to fork this repository and contribute enhancements or bug fixes. Open a pull request with a detailed explanation of your changes.

## License

This project is open-source and available under the [MIT License](LICENSE).




