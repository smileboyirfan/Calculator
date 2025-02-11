## Calculator Project

### Overview
This is a simple calculator web application that allows users to perform basic arithmetic operations like addition, subtraction, multiplication, and division. The application is built using HTML, CSS, and JavaScript.

### Features
- **Basic Arithmetic Operations:** Supports addition (`+`), subtraction (`-`), multiplication (`*`), division (`/`), and modulus (`%`).
- **Clear and Backspace Functionality:** Users can clear the entire input (`AC`) or remove the last entered character (`X`).
- **Positive/Negative Toggle:** The `±` button allows users to toggle the sign of the current number.
- **Decimal Support:** Users can enter decimal numbers using the `.` button.
- **Instant Calculation:** Clicking `=` evaluates the expression and displays the result.

### File Structure
- **index.html:** Contains the structure of the calculator, including buttons and input fields.
- **style.css:** Handles the styling, making the calculator visually appealing.
- **script.js:** Contains the logic for handling button clicks, calculations, and other interactive functionalities.

### How It Works
1. Users can enter numbers and operators by clicking the respective buttons.
2. The entered expression is displayed in the input field.
3. Clicking `=` evaluates the expression using JavaScript's `eval()` function and displays the result.
4. The `AC` button clears the entire input, while the `X` button removes the last character.
5. The calculator prevents consecutive operators from being entered to ensure valid expressions.

### Technologies Used
- **HTML:** Structuring the calculator layout.
- **CSS:** Styling for an enhanced user experience.
- **JavaScript:** Handling input, calculations, and button events.

### Improvements & Future Enhancements
- Adding keyboard support for better usability.
- Implementing parentheses for complex calculations.
- Enhancing UI with animations and themes.
