Milestone Project 1
This is my First Milestone Project for the Code Institute’s Diploma in Full Stack Development.

The Project Brief
The brief was to create a Web Front End for a fictional 60's band however i decided to build responsive website for Auto repair Garage



Deployment
Notepad++ run on my local windows based machine was used in conjunction with the Chrome browser to develop the initial Bootstrap based layout for the index.html webpage. This was then customised further using Chrome Devtools and CSS. Once comfortable with the page structure and layout I applied the baseline theme to the booking, look, listen and about.html pages. Note* Discrete images were used for the carousel on each of the web pages. The files were uploaded to the Cloud9 IDE, which I used for version control, and an initial git commit was performed. The Cloud9 repo was then bound to a remote github repo and they were synchronised. The newsletter modal, booking submit form, listen and READme.md files were then completed and a second commit was initialised.

Github Pages was then used to host and deploy the site at the following url:




Testing
Responsive Design
During all phases of development I used Chrome Devtools to test the responsive design functionality. For instance I noted that the Navbar text wrapped before and after certain breakpoints so used media queries to scale the fonts and transition more smoothly from one breakpoint to another.


Browser Rendering
Once the webpages were completed I ran trials using Opera, Edge, IE-11 and Firefox to confirm functionality, html, css & boostrap rendering was consistent across various web browsers. This enabled me to identify inconsistent flexbox display behaviour for the section element in the booking page when using ie version 11. Per Github url below the issue appears to be a bug associated max-width config applied to nested elements using flex display. The abnormal behaviour resulted in the form input elements aligning to the right of the page as opposed to the center. I overcame the problem by adding an addtional class to the booking-form column that specifically targetted the bug. During this process I also decided to change the section & booking request row margins and padding for smaller breakpoints under 560px using media queries.



HTML/CSS Syntax Validation
Prior to submission I validated the html and css code syntax/structure using the below W3C validators, amending errors where they were highlighted.

https://jigsaw.w3.org/css-validator/#validate_by_input
https://validator.w3.org/#validate_by_input



Content
The sample photos, audio and video clips provided by the Code Institute were for The Monkees.
I've dowloaded additional content from a number of sources and modified them to facilitate the theme of this fictional website. Sources include but were not limited to:
