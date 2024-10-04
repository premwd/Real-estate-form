Contact Form Project
This project is a responsive contact form built using HTML, CSS (Tailwind CSS), and JavaScript. The form allows users to submit their details (first name, last name, email, and phone number) along with selecting a property type and location. The form data is validated before submission and sent to a Google Script endpoint, which handles the form data processing.

Table of Contents
Features
Technologies Used
Setup
Usage
Validation Logic
Contribution
License
Features
Responsive Design: The form is responsive and works well on devices of various screen sizes.
Smooth Scrollable List: Property locations are presented in a smooth horizontal scrollable list.
Selectable Items: Users can select property types and locations, with a visual indicator for selected items.
Form Validation: Form fields are validated to ensure correct inputs before submission. Errors are displayed if any field is invalid.
Dynamic Submission Button: The submit button changes text to "Submitting..." during form submission.
Google Script Integration: Form data is sent to a Google Script backend for processing.
Technologies Used
HTML5
CSS3 (Tailwind CSS)
JavaScript
Google Apps Script (for backend processing)
Setup
To run this project locally:

Clone the repository
git clone https://github.com/yourusername/contact-form-project.git
Open the index.html file in any web browser.
External Dependencies:
Tailwind CSS:
Used for styling and responsiveness.
Loaded via CDN in the <head> tag
<script src="https://cdn.tailwindcss.com"></script>
