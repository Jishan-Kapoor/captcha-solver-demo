# Captcha Solver Web Application

## Summary
This static web application allows users to solve captchas by providing the URL of the captcha image. By inputting the captcha image URL as a query parameter, users can decode the captcha and view the solved result.

## Setup
1. Fork the repository.
2. Upload the captcha image you want to solve to a publicly accessible URL.
3. Append `?url=YOUR_CAPTCHA_IMAGE_URL` to the GitHub Pages URL to use the application.

## Usage
To access the captcha solver page, visit the following link: [Captcha Solver Page](https://username.github.io/captcha-solver).
Use query parameters to configure the application:
- `url`: URL of the captcha image to solve.
Key features include:
- Decoding captchas from external URLs
- Viewing the solved captcha result

## Code Explanation
The application is built using HTML and JavaScript. When the page loads, the script reads the URL query parameter and fetches the captcha image for analysis. The captcha-solving algorithm then processes the image and displays the solved captcha to the user.

Key libraries used:
- None

Important logic:
- Retrieving the captcha image based on the provided URL
- Processing and analyzing the captcha image to extract the text content

## License
This project is licensed under the MIT License.
```