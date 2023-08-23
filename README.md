

# HTML Utilities

This is a set of utility functions for creating HTML elements with attributes. These utility functions are designed to simplify the process of generating common HTML elements in your web projects.

## Installation

1. Download the `utilities.js` file from this repository.
2. Include the script in your HTML file:

```html
<script src="path/to/utilities.js"></script>
```

Replace `"path/to/utilities.js"` with the actual path to the downloaded `utilities.js` file.

## Usage

You can use these utility functions to easily create HTML elements with attributes. Here are some examples:

### Creating a Form

```javascript
const form = utilities.createForm('my-form', 'formId', 'submit', 'post');
document.body.appendChild(form);
```

### Creating a Button

```javascript
const button = utilities.createButton('btn-primary', 'btnSubmit', 'submit', 'Submit');
document.body.appendChild(button);
```

### Creating an Input Field

```javascript
const input = utilities.createInput('input-field', 'usernameInput', 'text', 'username', 'Enter your username', true);
document.body.appendChild(input);
```

... and so on for other utility functions ...

## Available Functions

### `createForm(className, id, action, method)`

Create and return a form element with specified attributes.

### `createButton(className, id, type, innerText)`

Create and return a button element with specified attributes.

### `createInput(className, id, inputType, name, placeholder, isRequired)`

Create and return an input element with specified attributes.

... other utility functions ...

## Contributing

Contributions are welcome! If you have ideas for additional utility functions, improvements to the existing code, or bug fixes, please feel free to open issues or pull requests.

## License

This project have no lisensing and is a free open source javascript utility functions for html tags, feel free to use it and edit it however you want and document your edits in this readme.

---

```javascript
// HTML Utilities
const utilities = {
  // ... your utility functions ...
};
export default utilities;
```

Feel free to copy and paste this Markdown code as your README content. Replace `"path/to/utilities.js"` with the actual path to your `utilities.js` file.
