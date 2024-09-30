# wd101
# Registration_form-wd101-capstone-project
This is my wd101 capstone project -Registration form.This project is a simple registration form that accepts user inputs, stores the data in local storage, and displays the user entries in a table. The form is built with **HTML**, **CSS** (using **Tailwind CSS** for styling), and **JavaScript** for functionality. The project is hosted using **GitHub Pages**.

## Table of Contents

- [Features](#features)
- [Validations](#validations)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Project Structure](#project-structure)
- [License](#license)

## Features

- A clean and responsive registration form.
- Stores user entries in the browser’s local storage.
- Displays the stored data in a dynamic table.
- Includes form validations, including:
  - Name, email, and password fields are required.
  - Date of Birth field only accepts users aged between 18 and 55.
  - Users must accept the terms and conditions to submit the form.
- Modern and attractive UI design with Tailwind CSS.

## Validations

- **Name Field**: The name field is required, and if not properly filled, the input will display a red border when focused.
- **Email Field**: The email field requires a valid email format.
- **Password Field**: The password field is required.
- **Date of Birth**: Validates that the date of birth is between the ages of 18 and 55.
- **Terms and Conditions**: The form cannot be submitted unless the checkbox is checked.

## Technologies Used

- **HTML5**: Markup language for structuring the form and table.
- **CSS (Tailwind CSS)**: Utility-first CSS framework for styling the UI.
- **JavaScript**: For form validation, handling local storage, and dynamically updating the user entries table.
- **GitHub Pages**: For hosting the project.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Alshifana/Registration_form-wd101-capstone-project.git
   ```

2. Navigate to the project folder:
   ```bash
   cd registration-form
   ```

3. Open `index.html` in your browser to see the form in action:
   ```bash
   open index.html
   ```

## Usage

1. Fill out the form fields, including name, email, password, and date of birth.
2. Accept the terms and conditions by checking the checkbox.
3. Click the **Submit** button to save the data.
4. The entered details will be stored in the browser’s local storage and displayed in a table below the form.
5. The table will update dynamically with each new form submission.

### Form Field IDs

The form uses the following field IDs:
- Name: `name`
- Email: `email`
- Password: `password`
- Date of Birth: `dob`
- Terms & Conditions: `acceptTerms`

These IDs must be present for the form validation and script functionality to work correctly.

## Deployment

This project is hosted using **GitHub Pages**. To deploy your own version:
1. Create a GitHub repository.
2. Add your project files (`index.html`, `index.js`, and any other assets).
3. Commit and push your changes to the `main` branch.
4. Go to your repository settings and enable GitHub Pages by selecting the `main` branch as the source.
5. After a few moments, your site will be live at `https://github.com/Alshifana/Registration_form-wd101-capstone-project.git`.

For a detailed guide on using GitHub Pages, refer to the [GitHub Pages Documentation](https://pages.github.com/).

## Project Structure

```bash
.
├── index.html        # Main HTML file for the registration form
├── index.js          # JavaScript file for form validation and handling local storage
├── README.md         # Project documentation
```


