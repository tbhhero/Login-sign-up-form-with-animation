# Login and Sign-Up Form with Animation

## Overview

This project is a responsive login and sign-up form with smooth animations using HTML, CSS, and JavaScript. The form includes a toggle feature to switch between sign-in and sign-up views, along with dynamic content animations.

## Features

- **Responsive Design**: Adapts to different screen sizes and devices.
- **Animated Transitions**: Smooth animations between sign-in and sign-up forms.
- **Modern UI**: Uses the Poppins font and a vibrant color scheme.
- **Easy Toggle**: Switch between sign-in and sign-up forms with a button click.

## Project Structure

- `index.html`: The main HTML file containing the structure of the form.
- `style.css`: Contains the styles and animations for the form.
- `script.js`: Handles the toggle functionality between sign-in and sign-up forms.

## Getting Started

To run this project locally, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/login-signup-form.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd login-signup-form
   ```

3. **Open the `index.html` File**

   Open `index.html` in your preferred web browser to view the form.

## Features

### Sign-In Form

- Username
- Password
- Forgot Password link

### Sign-Up Form

- Username
- Email
- Password
- Confirm Password
- Sign-Up button

## CSS Animations

The form elements have animations to enhance user experience:

- **Scale Animation**: Forms and social list items scale up when activated.
- **Slide Animation**: Text and images slide in from the sides based on the active form.

## JavaScript Functionality

The JavaScript file includes a function to toggle between sign-in and sign-up forms:

```javascript
let container = document.getElementById('container')

toggle = () => {
	container.classList.toggle('sign-in')
	container.classList.toggle('sign-up')
}

setTimeout(() => {
	container.classList.add('sign-in')
}, 200)
```

## Customization

Feel free to customize the colors, fonts, and animations by editing the `style.css` file. You can also modify the HTML structure and JavaScript functionality according to your needs.

## Dependencies

- **Font**: Poppins from Google Fonts

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- [Poppins Font](https://fonts.google.com/specimen/Poppins) - Font used in the project.
- [Boxicons](https://boxicons.com/) - Icon library used for the input icons.

