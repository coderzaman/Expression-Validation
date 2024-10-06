### Project Name: Expression-Validation

This project demonstrates form validation using regular expressions (RegEx). It includes a select input where users can choose validation types like name, email, password, phone number, and postal code. Users then input the respective values in a text field, and upon clicking the validation button, a message will show if the input is valid or not based on the selected option.

### Features:
- **Select Validation Type**: Users can select from a list of options including name, email, password, phone number, and postal code.
- **Input Field Validation**: Users enter data into a text field, and the input is validated based on the selected option.
- **Validation Messages**: Displays messages like "Valid" or "Invalid" depending on the input value and validation type.

### Regular Expressions Used:
- **Phone Number**: `/^(\+)?(88)?01[0-9]{9}$/` — Validates Bangladeshi phone numbers (with or without country code).
- **Email**: `/^([a-zA-Z0-9]\.?)+[^\.]@([a-zA-Z0-9]\.?)+[^\.]$/` — Ensures valid email format.
- **Postal Code**: `/^[0-9]{4}$/` — Validates a 4-digit postal code.
- **Password**: `/^(?=.*[A-Z])(?=.*[a-z])(?=.*\d)(?=.*[\W_])[^\s]{6,}$/` — Validates a password with at least one uppercase letter, lowercase letter, number, and special character, with no spaces and at least 6 characters.
- **Username**: `/^[a-zA-Z][a-zA-Z0-9._]{2,29}$/` — Allows usernames starting with a letter, followed by alphanumeric characters, periods, or underscores, between 3 to 30 characters long.
- **Name**: `/^[A-Z][a-zA-Z]+([ '-][A-Z][a-zA-Z]+)*$/` — Validates names starting with an uppercase letter, allowing spaces, apostrophes, or hyphens between words.

### Technologies Used:
- JavaScript
- HTML
- Regular Expressions (RegEx)

### How to clone the project:
1. Clone the repository using the following command:
   ```bash
   git clone https://github.com/coderzaman/expression-validation.git
   ```

2. Open the `index.html` file in your browser to test the validation functionality.

Feel free to contribute or modify!
