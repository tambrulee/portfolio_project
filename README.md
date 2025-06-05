# Portfolio Project

<img src="assets/images/readme.png" alt="Welcome to my portfolio project">

## About Project

This portfolio showcases my web development skills, featuring both completed and ongoing projects. It's designed to appeal to recruiters, collaborators, and fellow developers by blending creativity with technical ability.

<a href="https://tambrulee.github.io/Portfolio_Project/index.html">Click here to view my deployed website in GitHub</a>

The site features an anime-inspired aesthetic, including a Studio Ghibli-style illustration generated via DALL·E through ChatGPT, based on a real-life photo of me.

Beyond web development, I’ve included design work to set myself apart—blending technical ability with creative flair and offering a glimpse of my personality.

The project was built using HTML5, CSS3, Bootstrap, and SCSS. While my use of SCSS is still developing, I plan to build on it in future work. Typography is set in Bebas Neue (from Google Fonts) and Avenir.

<img src="assets/images/selfie.jpg" alt="A real life photo of me">

**A picture of me that I converted into an AI image**

<img src="assets/images/about.png" alt="Home page photo created in ChatGPT">

**Hero image for home page**

<img src="assets/images/projects.png" alt="Home page photo created in ChatGPT">

**Hero image for project page**

<img src="assets/images/contact.png" alt="Home page photo created in ChatGPT">

**Hero image for contact page**

## Built With

### Technologies
* **HTML5** - Basic website structure, semantic markup, and accessibility
* **CSS3** - General theme customization
* **Bootstrap** - Mobile responsive containers, navigation, footer, scrollspy, and accordion
* **SCSS** - Used for styling, particularly in customizing the theme and organizing styles more efficiently.

### Styling

* **Font Awesome** - Footer Icons
* **Google Fonts** - Importing Avenir & Bebas Neue
* **DALL-E** - AI-generated illustrations for a creative, personalized touch.

### Importing SCSS
For this project I imported SCSS. Although it isn't my first attempt, it is my first successful attempt.

#### Errors
It took several attempts to install SCSS successfully. I used npm/ sudo to load SCSS via the terminal on macOS. 

* First issue was that I was trying to load SCSS into the wrong directory - I changed directory and this seemed to work
<img src="assets/images/readme/code-testing/installing-scss.png" alt="Screenshot of npm/sudo scss loading error message in macOS terminal">
<img src="assets/images/readme/code-testing/html-checking-2.png" alt="Screenshot of npm/sudo scss loading error message in macOS terminal">
<img src="assets/images/readme/code-testing/installing-scss-3.png" alt="Screenshot of npm/sudo scss loading error message in macOS terminal">

* Second issue was use of incorrect syntax when trying to watch SCSS - resolved with the assistance of ChatGPT.
<img src="assets/images/readme/code-testing/installing-scss-6.png" alt="Screenshot of npm/sudo scss loading message in macOS terminal">
<img src="assets/images/readme/code-testing/installing-scss-7.png" alt="Screenshot of npm/sudo scss loading message in macOS terminal">
<img src="assets/images/readme/code-testing/chatgpt-sudo.png" alt="Screenshot of ChatGPT solution">

## User Stories

These user stories and acceptance criteria formed the foundation of the design. I aimed to keep the language and layout simple to cater to both technical and non-technical users. Clear call-to-action buttons guide users seamlessly between the homepage, projects, and contact pages.

GitHub links allow technical users to explore my code, while a LinkedIn link offers recruiters a quick way to review my resume and reach out.

The site is compact and efficiently designed, making it easy for visitors to learn about me and navigate to my work without feeling overwhelmed.

### 1. Hiring Manager Reviewing My Portfolio

**As a hiring manager**,  
I want to quickly understand the candidate’s technical skills, projects, and experience,  
So that I can determine if they are a good fit for the role.

**Acceptance Criteria:**
- A clear and concise "About Me" section.

- A well-organized list of projects with descriptions, technologies used, and links to code/demo.
- A section highlighting key skills and certifications.

### 2. Senior Developer Assessing My Code

**As a senior developer**,  
I want to review clean, well-structured code from the candidate’s projects,  
So that I can assess their coding ability and problem-solving skills.

**Acceptance Criteria:**
- Projects include a GitHub repository with well-documented README files.
- Code is formatted, commented, and follows best practices.
- A section describing challenges faced and solutions implemented.

### 3. Recruiter Looking for a Junior Developer

**As a recruiter**,  
I want to quickly scan the candidate’s experience and projects,  
So that I can decide whether to reach out for an interview.

**Acceptance Criteria:**
- A prominent section with key skills and technologies.
- A contact section with LinkedIn, email, and GitHub links.
- A visually appealing layout that is easy to navigate.

### 4. Fellow Developer Looking for Collaboration

**As a fellow developer**,  
I want to see if the candidate has open-source projects or shared interests,  
So that I can reach out for potential collaboration.

**Acceptance Criteria:**
- A section showcasing open-source contributions or side projects.
- Clear project descriptions with collaboration details.
- A way to contact the candidate or connect via GitHub.

### 5. Non-Technical Visitor Curious About My Work

**As a non-technical visitor**,  
I want to understand what the candidate does without needing deep technical knowledge,  
So that I can appreciate their skills and experience.

**Acceptance Criteria:**
- A simple, jargon-free introduction.
- Brief descriptions of projects with real-world applications.
- A visually engaging portfolio with screenshots or demos.

## Wire Frames

I drew up some rough wireframes. The final outcome came out quite close to the mockups, except it has a more compact layout with reduced whitespace. I also eventually decided to remove the badges as I struggled to place them in a way that would be mobile-optimized.

<img src="assets/images/readme/wireframes/mobile_view.png" alt="Wireframe mockups">
<img src="assets/images/readme/wireframes/front_page.png" alt="Wireframe mockups">
<img src="assets/images/readme/wireframes/projects_page.png" alt="Wireframe mockups">
<img src="assets/images/readme/wireframes/contact_page.png" alt="Wireframe mockups">

## Pages

### 1. Home / About Me

This is the landing page when the user first visits the website. It's split into three main sections: a hero image, a body of text describing me, and a banner showing icons of the coding languages I use.

I decided to use the Scrollspy feature after applying it to the Project page and liking the way it looked. In terms of UX, I thought it went well with the overall theme and made the information look nicely compact on the page.

I designed the homepage so that the spyscroll buttons work only on tablet and mobile, but on desktop the buttons disappear as I felt they were redundant as there was not enough content. So I set display to hidden using a media query with a view to unhide as my portfolio grows. 

<img src="assets/images/readme/code-testing/mobile_responsiveness_home.png" alt="Responsive mobile optimised homepage">

**Features:**
- Hero image
- A short bio  
- Key skills / tech stack badges  
- Call-to-action button that leads to Projects page

### 2. Projects

This second page of the website showcases some of my ongoing projects. It uses a scrollspy with a navigation bar, so viewers can easily find each project and learn more about it.

<img src="assets/images/readme/code-testing/mobile_responsiveness_projects.png.png" alt="Responsive mobile optimised projects page">

**Features**
- A Bootstrap scrollspy window for easy navigation.
- Descriptions of each project, the technology used, and links to live demos or code repositories.

### 3. Contact / Connect

A quick, simple way for people to reach me or connect further.

<img src="assets/images/readme/code-testing/mobile_responsiveness_contacts.png.png" alt="Responsive mobile optimised contact page">

**Features:**
- A friendly message welcoming visitors to get in touch.
- My email address, LinkedIn, GitHub, and other social media links.

## HTML Testing

* HTML was tested using: <a href="https://validator.w3.org/">Nu Html Checker</a>

### Fixing Errors
Here's a list of errors flagged up by the W3 tester and how I fixed them:

* Removed '/' from all internal links to pages and files
* Closed main tag
* Closed all div elements
* Added spaces between attributes 
<img src="assets/images/readme/code-testing/page-testing-1.png">

* Removed all duplicate IDs and replaced them with classes where appropriate

<img src="assets/images/readme/code-testing/page-testing-2.png">

* Recoded all sections where there was a button tag nested within an a tag, so that it is an a tag with a button class so that CSS and styling are picked up.

<img src="assets/images/readme/code-testing/page-testing-3.png">


### Home Page - Issues Fixed
<img src="assets/images/README/Code testing/Screenshot 2025-04-22 at 22.53.16.png">

### Projects Page - Issues Fixed
<img src="assets/images/README/Code testing/Screenshot 2025-04-22 at 23.12.47.png">

### Contact Page - Issues Fixed
<img src="assets/images/README/Code testing/Screenshot 2025-04-22 at 23.18.09.png">

## CSS Testing

HTML was tested using: <a href="https://jigsaw.w3.org/css-validator/#validate_by_input" target="_blank">CSS Validation Service</a>

No errors or issues found with CSS

<img src="assets/images/README/Code testing/Screenshot 2025-04-22 at 23.19.04.png">

## Lighthouse Testing

I tested the website in lighthouse. Overall I was happy with the results, especially for accessibility. If I had more time I would look at the website performance, otherwise I'm happy that loading times and website speed is gernerally okay. 

### Home Page - Lighthouse Test - Mobile
<img src="assets/images/README/Code testing/Lighthouse_home_mobile.png">

### Home Page - Lighthouse Test - Desktop
<img src="assets/images/README/Code testing/Lighthouse_home_desktop.png">

### Projects - Lighthouse Test - Mobile
<img src="assets/images/README/Code testing/Lighthouse_projects_mobile.png">

### Projects - Lighthouse Test - Desktop
<img src="assets/images/README/Code testing/Lighthouse_projects_desktop.png">

### Contact - Lighthouse Test - Mobile
<img src="assets/images/README/Code testing/Lighthouse_contact_mobile.png">

### Contact - Lighthouse Test - Desktop
<img src="assets/images/README/Code testing/Lighthouse_contact_desktop.png">

## Mobile Responsiveness
I used the <a href="https://ui.dev/amiresponsive" target="_blank">Am I Responsive?</a> tool to test the mobile responsiveness of each of my web pages.

#### Home Page - Mobile Responsiveness
<img src="assets/images/README/Code testing/Mobile_responsiveness_home.png">

#### Projects Page - Mobile Responsiveness
<img src="assets/images/README/Code testing/Mobile_responsiveness_projects.png">

#### Contact Page - Mobile Responsiveness
<img src="assets/images/README/Code testing/Mobile_responsiveness_contacts.png">





## GitHub

### Connecting to GitHub via VS Code

- I downloaded GitHub Codespaces

- Once connected I could connect to my repositories in GitHub

- I used the interactive panel to do my commits and to push my commits to Git Hub

### Deployment

* First I created a folder for my project on my local hard drive
<br>
<img src="assets/images/README/GitHub Deployment/local_files.png">
<br><br>

* Then I installed GitHub Codespaces into VS Code
<br>
<img src="assets/images/README/GitHub Deployment/codespaces_install.png">
<br><br>

* From there I was able to write my first few files. Write my commits and push my work via the interface in source control which provides easy to use commit, push and pull buttons.
<br>
<img src="assets/images/README/GitHub Deployment/source_control.png">
<br><br>

* I could then check GitHub which was updating with each push as expected. 
<br>
<img src="assets/images/README/GitHub Deployment/github_files.png">
<br><br>

* To deploy the project I used Pages section in my GitHub project which I used throughout the creative process to ensure the project was being deployed correctly. I did have an
<br>
<img src="assets/images/README/GitHub Deployment/github_pages.png">
<br><br>

*  Here is my project deployed in GitHub. I did have some issues with setup at first, then after researching the issue I realised that my project was set to private to I  set it to public. Further issue images not showing and links going to a 404 page, this was resolved by removing the first '/' out of the links. 
<br>
<img src="assets/images/README/GitHub Deployment/github_deploy.png">

#### Test 1
First deployment was unsuccessful. The index.html (Home) page was loading but the 'Project' and 'Contact' pages were not. I simply removed the '/' from in front of the file paths and tried again which worked.
<img src="assets/images/README/Code testing/Deployment to GitHub.png">

#### Test 2
As per above, the second attempt was successful and the website is no successfully deployed. Check it out here:

<a href="https://tambrulee.github.io/Portfolio_Project/index.html">Click here to view my deployed website in GitHub</a>

<img src="assets/images/README/Code testing/GitHub - Deployed.png">

## Known Bugs

### Main navigation bar 
The navigation bar does not stretch all the way across the top of the screen at a 990px (min-width) and upwards resolution. This is an unintended glitch, but overall, it doesn't detract from the usability or the overall look of the website.

### Scrollspy buttons - Project page
Making the scrollspy buttons on the Project page disappear at 900px (min width) was a design choice as the container fit the screen and the buttons became redundant.

## Attribution

### Bootstrap
The portfolio heavily depends on Bootstrap for mobile responsiveness. The navigation, footer, containers, flex grids, scrollspy, and accordion all come from the Bootstrap library.
