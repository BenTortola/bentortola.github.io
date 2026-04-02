Student Name: Ben Tortola
Student NetID: B01039641

--------------------------------------------------
1. Folder Structure & Relative Paths
--------------------------------------------------

Project Folder:
- index.html
- gallery.html
- about.html
- style.css
- README.txt
- A2_CodeReview.pdf
- A2_Design.pdf
- images/ (folder)
- videos/ (folder)
- audio/ (folder)

Relative Paths Used:

Images:
images/image1.jpg
images/image2.jpg
images/image3.jpg
images/image4.jpg
images/favicon.png

Video:
videos/Eye of Clthulhu Animation.mp4

Audio:
audio/intro.mp3

All links use relative paths. No absolute file paths were used.

--------------------------------------------------
2. Website Structure
--------------------------------------------------

The website contains three pages:

1. index.html (Home Page)
2. gallery.html (Gallery Page)
3. about.html (About Page)

Each page contains a navigation menu linking to the other pages.

The homepage contains JavaScript features such as:
- A welcome notification
- A conditional prompt
- A theme color changer
- An event handler

--------------------------------------------------
3. Elements Included
--------------------------------------------------

Images:
Purpose: Display visual content on the website.
All images include alt text and specific width and height.

Example:
<img src="images/image1.jpg" alt="Animation artwork" width="400" height="250">

Video (Local):
Purpose: Displays a locally stored MP4 animation video.

Example:
<video width="400" controls>
    <source src="videos/Eye of Clthulhu Animation.mp4" type="video/mp4">
</video>

Video (External – YouTube):
Purpose: Provides an embedded external video.

Audio:
Purpose: Plays an audio file with controls.

Example:
<audio controls>
    <source src="audio/intro.mp3" type="audio/mpeg">
</audio>

Navigation:
Purpose: Allows users to move between pages.

Lists:
- One unordered list
- One ordered list
- One nested list

Table:
Purpose: Displays structured information in rows and columns.

Form:
Purpose: Allows users to input their name and message using text input and textarea.

--------------------------------------------------
4. JavaScript Functions
--------------------------------------------------

Notification (alert):
Displays a welcome message when the homepage loads (only once per session).

Conditional (if / else):
Prompts the user to answer if they like animation and displays a different
message depending on their response.

Color Theme Changer:
Allows the user to switch between Dark Theme, Light Theme, and Blue Theme.
Themes persist across pages using localStorage.

Event Handler:
Clicking the homepage image triggers a JavaScript function that displays
a message before navigating to the gallery page.

--------------------------------------------------
5. CSS Styling (Assignment 3)
--------------------------------------------------

The website uses an external stylesheet (style.css).

The following elements are styled:

- Images (border, padding, margin)
- Navigation links (color, hover effects)
- Lists (spacing and formatting)
- Table (borders, colors, layout)
- Buttons (hover and transition effects)
- Form inputs and textarea
- General layout and spacing

--------------------------------------------------
6. CSS Selectors Used
--------------------------------------------------

Universal selector:
* { ... }

Multiple selector:
h1, h2, h3 { ... }

Child selector:
ul > li { ... }

Sibling selector:
h2 ~ p { ... }

Adjacent sibling selector:
h2 + ol { ... }

Attribute selector:
a[href] { ... }

Pseudo-element selector:
p::first-letter { ... }

--------------------------------------------------
7. Layout Features
--------------------------------------------------

Flexbox:
Used on index.html in the hero section to align text and image side by side.

Grid:
Used on gallery.html to create a responsive photo gallery layout.

--------------------------------------------------
8. Responsive Design
--------------------------------------------------

Media queries were used to support:

- Desktop layout (default)
- Tablet layout (max-width: 900px)
- Mobile layout (max-width: 600px)

Adjustments include:
- Gallery changing from 3 → 2 → 1 columns
- Navigation stacking vertically on mobile
- Buttons resizing and stacking
- Images and videos resizing dynamically

A viewport meta tag was added for proper scaling on mobile devices.

--------------------------------------------------
9. Accessibility
--------------------------------------------------

The website follows basic accessibility practices:

- All images include alt text
- Buttons are used for interactive elements
- Clear color contrast for readability
- Labels included for form inputs
- Responsive design improves usability on all devices

--------------------------------------------------
10. Code Notes
--------------------------------------------------

Reused Code From Assignment 1:

The HTML structure, navigation system, and overall layout of the website
were originally created in Assignment 1. These files include:

- index.html
- gallery.html
- about.html

Assignment 2 and 3 expand on this code by adding:

- JavaScript interactivity
- CSS styling and layout
- Responsive design features
- Improved accessibility

--------------------------------------------------
11. References (ACM Format)
--------------------------------------------------

Exoskellet. 2023. Animation Video. YouTube. Available at: https://www.youtube.com

15TOFU. 2023. Favicon Image. DeviantArt. Available at: https://www.deviantart.com

VoidInferserka. 2023. Artwork Image. Pinterest. Available at: https://www.pinterest.com

MyInstants. 2023. Sound Effect. MyInstants Soundboard. Available at: https://www.myinstants.com

--------------------------------------------------
12. Additional Documents
--------------------------------------------------

A2_CodeReview.pdf – explains two examples of HTML code improved using JavaScript.

A2_Design.pdf – contains desktop, tablet, and mobile wireframes and the website linking diagram.

--------------------------------------------------
13. Bonus: Free Hosting
--------------------------------------------------

The website has been hosted online using GitHub Pages.

Live website URL:
https://bentortola.github.io