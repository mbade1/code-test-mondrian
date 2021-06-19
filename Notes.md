## Times

Start time: 10:50 AM
Painting: 1:00 PM
Mobile: 2:00 PM, committed with extra touches at 2:30
Final commit: 2:50 PM

## Initial Thoughts

600px+

- Frame the painting (flex, centered div) with padding for the canvas and an elegant border (styles TBD) **DONE**
- Use a GRID layout, spanning over the dimensions of the painting **DONE**
- Get the dimensions of each rectangle, then recreate with a grid layout **DONE**
- 28 rectangles in total **DONE**
- Set a default black border on each rectangle (rectangle class) **DONE**
- Refactor for finishing touches

600px-

- Turn flex direction into a column, so that divs of previous grid rectangles line up vertically. **DONE**
- Each div is a container for each gridded color div (rectangle), based on the additional class name from the large image.
- Get number of rectangles for each color, then make that number of rectangles the correlating background color. **DONE**
  - Ex: 4 red rectangles; grab 4 child rectangles and make them red **DONE**

## Process

This was a fun challenge that certainly embraced my CSS knowledge! The overall process for this challenge is as follows:

### Initial Thoughts

I wrote out my initial thoughts for this project above, and added to them as I went along. I read the requirements and instructions twice, and noted the following sentence: "His painting No. VI / Composition No. II is typical of this movement, featuring a **grid** of rectangular shapes in shades of white, gray and black, accented by bold primary colors." That clue led me to create a gridded layout.

### HTML

After knowing I would be making a gridded format, I created the DOM tree for each rectangle as a div. I made a header with the title, artist, and price and also created a container, frame, and painting divs. Within the painting I made 28 child divs, with the class name of rectangle. After making the structure, I moved to CSS

### CSS

This was the largest part of the challenge. I used the provided image as a guide as to how my CSS/HTML painting would look, and created dimensions for each individual rectangle. I created a grid styled display with 20 rows and columns. I then designed each rectangle with the correct number of rows/columns and their color, according to the original painting. After slowly piecing together each individual rectangle, I moved onto the border thickness of each rectangle. Some have thick borders, others are thing. So, I utilized my palette of color variables and created each colored border. I added some padding with a white background for the frame, along with a nice gold border, then moved onto mobile (under 600px) styling.

### Mobile

I changed from a grid display to a flex display, to make a column of divs. After counting the number of colored boxes in the painting, I grabbed that number of child elements within the painting, and changed their background color accordingly, which knocked off the mobile view requirement. I continued styling by adding margin-bottom properties at the last colored div, and also created a color palette at the bottom of the page, with a total number of colored boxes.

### Clean Up & Submission

Before submitting, I had roughly 40 minutes to clean up. I refactored some of the HTML and CSS, making things clean, and DRYing up my code. If I redid this project, I would utilize JS for the Color Palette, and add some more styling to the header. I would stick with the same display styling (large screen to small screen), and I would also flip the hierarchy of the container and frame divs in the DOM hierarchy. I had a ton of fun making this, and I look forward to the next step!
