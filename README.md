# isys-102-hw4
A webpage that changes the previous homework assignment "isys-102-hw3" to work with grid and flexbox instead of float. For the ISYS-102 course at WVU Tech.

# How it's made
**Tech Used:** HTML and CSS

Since this webpage is an updated version of a previous assignment, you can check the repository for the previous version [here](https://github.com/cwilliams0926/isys-102-hw3.git). That version has the details for all of the styling involved on the page that isn't directly related to flexbox or grid, such as images, lists, and link buttons.

The first step was to remove all floats and clears from the stylesheet. The purpose of this assignment is to replace those with grid and flexbox, so that was priority number one. After doing this, the page obviously looked completely out of order, so the next step was to implement the new layout. I started with grid first, as getting the actual layout of the page seemed like the bigger problem to handle first.

I made the entire <body> tag a grid container. I then made the header, left column, right column, and footer use *grid-area* to have names. With *grid-template-areas* I specified the website layout. I also made the left column stay a constant width of 300px using *grid-template-columns*.

After getting the layout working properly using grid, I simply made the top navbar and right columns into flexboxes. It was as simple as adding *display: flex* to their containers. I added *flex-wrap: wrap* to the right column so that the image galleries line wrap. The assignment called for no changes to be made to the vertical navbar on the left, so I left that one alone.

There were some other changes and slight deviations from the previous assignment, but they weren't substantial enough to mention here.

# Lessons Learned
I already knew quite a bit about flexbox before starting this assignment, so the flexbox parts were quite simple. I was not as familiar with grid, so I had to read up a bit about it first before starting to change things around. I learned a bit about grid and how it works from this assignment, as well as how to easily make a simple webpage layout using it. Since this assignment is simply an update to a previous one, there isn't much to say here.
