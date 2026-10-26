# airasia-HW2
Assignment details 
Development Environment
Complete this assignment in a GitHub repository using GitHub Codespaces.

Create a new repository for HW2, open it in Codespaces, and build and test your website there. Commit and push all work to GitHub before submitting.

Use an organized folder structure. For example:

airasia-hw2/
├── login.php
├── card-list.php
├── card-details.php
├── card-add.php
├── card-update.php
├── ai-use.txt
├── css/
│   └── styles.css
└── images/
    └── gift-card.png
Required Pages
Create the following five pages using the exact filenames shown below.

Page	Filename	Requirements
Login Page	login.php	Include username and password fields and a Login button. The Login button must direct the user to card-list.php.
Gift Card List Page	card-list.php	Display a list of gift cards. Each gift card must show an image, card name, and points required. The gift card image or name must link to card-details.php. Include a link to card-add.php.
Gift Card Details Page	card-details.php	Display the details of one gift card, including its image, card name, card type, card value, and points required. Include a link to card-update.php. Only one details page is required. All gift-card links on the list page may lead to this one page.
Add Gift Card Page	card-add.php	Create an HTML form for adding a new gift card. Include labeled fields for Card Name, Card Type, Card Value, and Points Required. When the form is submitted, direct the user to card-list.php.
Update Gift Card Page	card-update.php	Create an HTML form for updating an existing gift card. Include labeled, prepopulated fields for Card Name, Card Type, Card Value, and Points Required. When the form is submitted, direct the user to card-list.php.
Because this is a static HTML and CSS assignment, form submission does not need to save information. The form action should simply simulate the next step in the workflow by taking the user to card-list.php.

Required Workflow
Use hyperlinks and form actions to connect the pages so a user can move through the application logically.

login.php→ card-list.php
card-list.php→ card-details.php
card-list.php→ card-add.php
card-details.php→ card-update.php
card-add.php→ card-list.php
card-update.php→ card-list.php
You may add Back, Cancel, or navigation links where helpful. Up to 5 points may be deducted if the required workflow is incomplete or broken.

AI Use Requirement
Use an AI assistant during your development process. You may use AI to:

Translate your HW1 wireframes into HTML page structures
Suggest semantic HTML elements and accessible form labels
Help create or improve CSS
Debug broken links, forms, images, or styling
Review your work against the assignment requirements
You must review and test all AI generated suggestions before including them in your project. You should be able to explain the purpose of the HTML elements, form attributes, hyperlinks, and CSS rules in your submitted website.

Create a file named ai-use.txt in the root of your repository. Include:

The AI tool or tools used
The prompt or prompts you used
A brief explanation of how AI supported your work
One example of an AI suggestion you tested, changed, or rejected
Requirements and Notes
Use PHP file extensions (.php) for all required web pages. At this stage, the files should contain HTML and CSS only. Do not use PHP programming logic, databases, or JavaScript yet.
Use the exact required filenames.
Use an external CSS file and link it to all pages.
Place images in an images folder and CSS in a css folder.
Use the provided gift-card image or another appropriate gift-card image.
Use realistic sample gift-card data.
Include labels for every form control.
Do not include Card ID as an editable form field because it is automatically generated.
You do not need to create a Delete Card page for HW2.
Make sure all pages, images, hyperlinks, and form actions work correctly in your browser.
Do not include irrelevant or unused files. Points may be deducted for clutter.
Learning Goals
Build HTML and CSS pages from approved wireframes and system requirements.
Apply Systems Analysis and Design from design through implementation.
Use semantic HTML, forms, hyperlinks, and CSS to support a business workflow.
Organize web application files in a GitHub repository.
Use GitHub Codespaces as a cloud-based development environment.
Use AI responsibly to support coding, testing, and improvement.
Submission
Submit the link to your GitHub repository in Canvas.

Before submitting, confirm that:

Your repository link works for the instructor.
The repository includes all five required HTML files.
Your CSS and image files are included.
ai-use.txt is included.
All required pages and workflow links function correctly.
All work has been committed and pushed to GitHub.

Grading Rubric

Criteria	
Gift Card List Page (card-list.php)	Displays a list of gift cards with an image, card name, and points required. Each card name or image links to card-details.php. Includes a link to card-add.php.	

Gift Card Details Page (card-details.php)	Displays one gift card’s image, card name, card type, card value, and points required. Includes a link to card-update.php.	

Add Gift Card Form (card-add.php)	Includes labeled form controls for Card Name, Card Type, Card Value, and Points Required. Form submission directs the user to card-list.php.	

Update Gift Card Form (card-update.php)	Includes labeled, prepopulated form controls for Card Name, Card Type, Card Value, and Points Required. Form submission directs the user to card-list.php.	

Login Page (login.php)	Includes username and password fields and a Login button that directs the user to card-list.php.	

Page Workflow and Repository Requirements	All required page links and form actions work. The GitHub repository link is submitted, required files are present, and the project is organized appropriately. 
