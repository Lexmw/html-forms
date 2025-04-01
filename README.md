# Demo Form

## Description
This is a simple HTML form that collects user input and displays the submitted data dynamically using JavaScript. The form includes various input fields to demonstrate different types of user input handling.

## Form Inputs

1. **Name (Text Input)**
   - Users enter their name in a text field.
   - Required field.

2. **Email (Email Input)**
   - Users enter their email address.
   - Required field.
   - Uses email validation.

3. **Gender (Radio Buttons)**
   - Users select one option: Male, Female, or Other.
   - Only one option can be selected.

4. **Interests (Checkboxes)**
   - Users can select multiple interests: Sports, Music, or Reading.
   - Users can choose none, one, or multiple options.

5. **Country (Dropdown Select Menu)**
   - Users select their country from a predefined list (USA, Canada, UK).

6. **Submit Button**
   - Users click to submit the form.

## Functionality
- When the user submits the form, JavaScript captures the input data.
- `event.preventDefault()` prevents the page from reloading.
- The collected form data is displayed dynamically on the page.
- The form data is also logged to the browser console for debugging.

## How to Use
1. Open the `index.html` file in a browser.
2. Fill in the form fields.
3. Click the "Submit" button.
4. The entered data will be displayed below the form and logged in the console.

This form is a great example of using JavaScript to handle form submissions dynamically without requiring a backend server.
