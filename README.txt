Student Name: Ben Tortola
Student NetID: B01039641

--------------------------------------------------
1. Folder Structure & Relative Paths
--------------------------------------------------

Project Folder:
- index.html
- gallery.html
- about.html
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

The homepage also contains JavaScript features such as a welcome notification,
a conditional prompt, a theme color changer, and an event handler.

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
Purpose: Provides an external video link.

Example:
<a href="https://www.youtube.com" target="_blank">Watch Video</a>

Audio:
Purpose: Plays an audio file with controls.

Example:
<audio controls>
    <source src="audio/intro.mp3" type="audio/mpeg">
</audio>

Navigation:
Purpose: Allows users to move between pages.
Implemented using anchor tags (<a>).

Lists:
- One unordered list
- One ordered list
- One nested list

Table:
Purpose: Displays structured information in rows and columns.

--------------------------------------------------
4. JavaScript Functions
--------------------------------------------------

Notification (alert):
Displays a welcome message when the homepage loads.

Conditional (if / else):
Prompts the user to answer if they like animation and displays a different
message depending on their response.

Color Theme Changer:
Allows the user to switch between Dark Theme, Light Theme, and Blue Theme
using buttons that modify the page colors with JavaScript.

Event Handler:
Clicking the homepage image triggers a JavaScript function that displays
a message before navigating to the gallery page.

--------------------------------------------------
5. References
--------------------------------------------------

Exoskellet. 2023. Animation Video. YouTube.
Available at: https://www.youtube.com

15TOFU. 2023. Favicon Image. DeviantArt.
Available at: https://www.deviantart.com

VoidInferserka. 2023. Artwork Image. Pinterest.
Available at: https://www.pinterest.com

MyInstants. 2023. Sound Effect. MyInstants Soundboard.
Available at: https://www.myinstants.com
--------------------------------------------------
6. Code Notes
--------------------------------------------------

Reused Code From Assignment 1:

The HTML structure, navigation system, and overall layout of the website
were originally created in Assignment 1. These files include:

- index.html
- gallery.html
- about.html

Assignment 2 expands on this code by adding JavaScript functionality
including:

• A welcome notification
• A conditional prompt using if/else
• A color theme changer with three themes
• An event handler triggered when the homepage image is clicked

All original HTML code from Assignment 1 was reused and modified to
support the new JavaScript features required for Assignment 2.

Additional Documents:

A2_CodeReview.pdf – explains two examples of HTML code improved using JavaScript.

A2_Design.pdf – contains the desktop, tablet, and mobile wireframes for
index.html and the website linking diagram.