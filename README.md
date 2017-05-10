# Information for Graders

Please add any information that might be relevant to the grader.  This file
will not be marked, but if the grader is confused by your work, or is looking
for more information about your design decisions, or is wondering why something
doesn't quite work he or she will look here to find some insight into your
thought process. The grader will also look at the documentation in your HTML,
CSS, and JavaScript files.

Arrangement of CSS files:
For the stylesheet, I'm using 1 main stylesheet `quiz.css` that is embeded in
my quiz.html file and it also contains CSS import
statements from other stylesheets in the `css` folder.
I did this since I think it would make my CSS code more organized and easy
to navigate through.

- `common.css` - Styles only specific to common tags used in the HTML doc
- `common.classes.css` - Styles for common classes that I used at many places
in my HTML and JS document
- `q1.css` - Specific styles for question 1
- `q2.css` - Specific styles for question 2
- `q3.css` - Specific styles for question 3
- `q4.css` - Specific styles for question 4
- `q5.css` - Specific styles for the end screen

Arrangement of contents inside `quiz.js` file:
- All helper functions are declared before the jQuery event handlers of
specific buttons

Brief notes of HTML DOM structure:
- Each question, including the end screen is within a section element
