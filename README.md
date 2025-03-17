# Required Field Styling

This project provides a simple CSS solution to indicate required input fields in forms with visual focus effects. It uses CSS to add a red asterisk (`*`) next to required fields and highlights them when the user focuses on the field.

## Features
- Adds a red asterisk to indicate required fields.
- Provides a visual focus effect when a required input field is selected.
- Easy to integrate into any web form.

## Usage

To use the styling, simply follow the steps below:

1. Include the `styles.css` file in your HTML file.
2. Add the `required` attribute to your input fields.
3. Use the provided CSS to apply the styles.

### Example HTML:

```html
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Required Field Example</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <form>
        <div>
            <input type="text" id="name" required>
            <label for="name">Name</label>
        </div>
    </form>
</body>
</html>

