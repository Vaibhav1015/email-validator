# email-validator

A simple JavaScript package to validate email addresses.

## Installation

You can install the package via npm:

```bash
npm install email-validation-util
```

## Usage

#### javascript

```javascript
const isValidEmail = require("email-validation-util");

console.log(isValidEmail("example@email.com")); // Output: true
console.log(isValidEmail("notanemail")); // Output: false
```

## Function Documentation

### **_isValidEmail(email: string): boolean_**

Checks if the provided email address is valid.

- **`email`**: The email address to validate.
- Returns **`true`** if the email address is valid, **`false`** otherwise.

## Example

#### javascript

```javascript
const isValidEmail = require("email-validation-util");

if (isValidEmail(userInput)) {
  console.log("Email address is valid");
} else {
  console.log("Invalid email address");
}
```
