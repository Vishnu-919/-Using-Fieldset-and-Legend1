# -Using-Fieldset-and-Legend1

# User Details Form

This is a simple HTML form designed to collect basic user information including first name and last name.

## 📄 Features

- Semantic and accessible form markup
- Uses `<fieldset>` and `<legend>` for grouping
- Input fields for first name and last name
- Submit button to send form data

## 🔧 Technologies Used

- HTML5

## 📋 Form Structure

The form includes:
- Two text inputs (`First Name`, `Last Name`)
- A submit button

## 🚀 How to Use

1. Open the `index.html` file in any web browser.
2. Enter your first and last name into the form fields.
3. Click the **Submit** button.

> Note: This form currently uses `action="#"`, so it does not send data anywhere. You can update the `action` attribute to point to your server or script if you want to handle the form data.

## ✅ Example HTML

```html
<form action="#" method="post">
  <fieldset>
    <legend>User Information</legend>
    <label for="fname">First Name:</label><br>
    <input type="text" id="fname" name="fname" required><br><br>

    <label for="lname">Last Name:</label><br>
    <input type="text" id="lname" name="lname" required><br><br>

    <input type="submit" value="Submit">
  </fieldset>
</form>



📁 File Structure
project-folder/
├── index.html
└── README.md

