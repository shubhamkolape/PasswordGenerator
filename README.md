# Password Generator App



# [Live Preview Here](https://shubhamkolape.github.io/PasswordGenerator/)


## Overview

This React-based password generator app allows you to generate random passwords with customizable length and character types. The app uses React hooks and state management to create and display passwords, and it also provides an option to copy the generated password to the clipboard.

## Features

- Password Generation: Set the desired password length and include numbers and special characters as needed.
- Copy to Clipboard: Easily copy the generated password to your clipboard.
- User-Friendly Interface: A clean and intuitive interface for a seamless user experience.

Technology Stack
1. React
2. JavaScript
3. HTML/CSS


How It Works
React Hooks
1. useState: Used for managing state variables for password length, number inclusion, character inclusion, and the generated password.

2. useRef: Creates a ref for the password input field to enable text selection and copying.

3. useCallback: Defines callback functions for password generation and copying to the clipboard, preventing unnecessary re-renders.

4. useEffect: Ensures that the password is updated dynamically based on user input by triggering the passwordGenerator function whenever relevant state variables change.


 ## Acknowledgments

I would like to express my gratitude to my teacher, [Hitesh Sir](https://www.linkedin.com/in/hiteshchoudhary/), for their guidance and support during the development of this password generator app. Their expertise and assistance have been invaluable in helping me create this project.


