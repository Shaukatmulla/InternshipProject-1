# Local Business Website

This project is a responsive website for a local business, featuring essential pages such as Home, About Us, Services, and Contact. The website includes a functional contact form integrated with Web3Forms for handling submissions and redirecting users to a thank you page after a successful submission.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to create a simple yet effective website for a local business. The website is fully responsive, adapting to various screen sizes including laptops, desktops, tablets, and mobile devices. It provides visitors with information about the business, the services offered, and a way to contact the business via a form.

## Features

- **Responsive Design:** The website is optimized to work on a variety of devices, ensuring a seamless user experience on desktop, tablet, and mobile devices.
- **Essential Pages:** The website includes the following pages:
  - Home
  - About Us
  - Services
  - Contact
- **Contact Form Integration:** The contact form is integrated with Web3Forms to handle submissions. Upon submission, users are redirected to a thank you page.
- **Thank You Page:** A dedicated thank you page is shown to users after they submit the contact form.

## Technologies Used

- **HTML5:** For the structure of the website.
- **CSS3:** For styling the website and making it responsive.
- **JavaScript:** For any interactive functionality.
- **Web3Forms:** For handling contact form submissions and sending them to a designated email address.

## Setup and Installation

To get this project up and running on your local machine, follow these steps:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Shaukatmulla/InternshipProject-1.git
    cd InternshipProject-1
    ```

2. **Open the Project:**

    Open the project in your preferred code editor.

3. **Replace the Web3Forms Access Key:**

    In `contact.html`, replace the placeholder `YOUR_ACCESS_KEY_HERE` with your actual Web3Forms access key.

    ```html
    <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">
    ```

4. **Replace the Redirect URL:**

    In `contact.html`, update the `_next` hidden input field with the correct URL to your thank you page.

    ```html
    <input type="hidden" name="redirect" value="https://yourdomain.com/thank-you.html">
    ```

5. **Run the Project:**

    You can run the project by simply opening `index.html` in your browser. For a better development experience, you might want to use a local development server.

## Usage

### Viewing the Website

You can view the website by opening the `index.html` file in your browser. The website should display correctly on various screen sizes, including desktops, tablets, and mobile devices.

### Submitting the Contact Form

To submit a message via the contact form:

1. Navigate to the "Contact" page.
2. Fill out the form fields.
3. Click "Send".

Upon submission, the form data is sent to the email address associated with your Web3Forms account, and the user is redirected to the thank you page.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and create a pull request with your changes.

### Steps to Contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m 'Add your message here'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Submit a pull request.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software as long as you include the original license.

---
