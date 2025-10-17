# Captcha Solver Project

## Project Description 
This project is a simple web application that takes a captcha image URL as a query parameter, displays the captcha, and simulates solving it within 15 seconds. The solved text is then displayed on the page and sent to a specified callback URL.

## Features 
- Display captcha from URL
- Simulate the solving of the captcha within 15 seconds
- Notify a callback URL with the solved text

## Usage 
To use the captcha solver, open the app with a URL parameter, e.g.: 
`index.html?url=https://c22blog.wordpress.com/wp-content/uploads/2010/10/input-black.gif`

### Example Callback
You can specify a callback URL to send the solved text by appending it as a `callback` parameter in the URL, e.g.: 
`index.html?url=<captcha-url>&callback=<your-callback-url>`

## Note
Please ensure that the provided captcha URL is accessible.