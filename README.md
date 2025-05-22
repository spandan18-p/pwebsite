# Portfolio Website

A responsive portfolio website with Google Sheets integration for contact form submissions.

## Features

- Responsive design that works on all devices
- Animated transitions and effects
- Project filtering
- Smooth scrolling
- Google Sheets integration for contact form

## Google Sheets Contact Form Setup

To connect the contact form to Google Sheets:

1. Create a new Google Sheet to store form submissions
2. Go to Extensions > Apps Script
3. Delete any code in the editor and paste the code from `google-sheets-script.txt`
4. Save the project with a name like "Contact Form Handler"
5. Click on Deploy > New deployment
6. Select "Web app" as the deployment type
7. Set the following:
   - Execute as: "Me"
   - Who has access: "Anyone"
8. Click "Deploy"
9. Copy the Web app URL provided after deployment
10. In your `script.js` file, replace `'https://script.google.com/macros/s/YOUR_SCRIPT_ID_HERE/exec'` with the URL you just copied

## Technology Stack

- HTML5
- CSS3
- JavaScript
- Google Apps Script (for form handling)

## Browser Support

- Chrome
- Firefox
- Safari
- Edge
- Opera

## Author

SPANDAN

## License

This project is open source and available under the [MIT License](LICENSE). 