## Flask Application Design

### HTML Files

**1. Base Template (base.html)**

- Layout for all pages of the website, defining common elements such as the header, navigation bar, and footer.
- Content from other HTML files gets injected into the body section.

**2. Home Page (index.html)**

- Homepage of the website, featuring information about the business, services offered, and contact details.

**3. Services Page (services.html)**

- Details different permanent makeup services provided by the business, including descriptions and pricing.

**4. About Us Page (about.html)**

- Introduces the business, team, and mission.

**5. Contact Page (contact.html)**

- Provides a form for potential clients to get in touch with the business, including contact information (address, phone number).

### Routes

**1. Home (/)**

- Route for the home page, returning a response with the `index.html` file.

**2. Services (/services)**

- Route for the services page, returning a response with the `services.html` file.

**3. About Us (/about)**

- Route for the about us page, returning a response with the `about.html` file.

**4. Contact (/contact)**

- Route for the contact page, returning a response with the `contact.html` file.

**5. Form Submission (/submit)**

- Route for handling form submissions from the contact page.
- Validates and processes the submitted data (e.g., saving the contact request to a database).