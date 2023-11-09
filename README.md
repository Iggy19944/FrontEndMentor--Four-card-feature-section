# FrontEndMentor--Four-card-feature-section

It was a fun project to make.

My main takeaways were.

1. When you give sizing to SVGs and also pictures most of the time its best to use px and not Rem, because if you give Rem your SVGs or Images will grow as your responsive design  by increasing screen size.

And do not type 
```<img src="images/icon-calculator.svg" alt="Calculator Icon" width="64px" height="64px">```
 but just type  
```<img src="images/icon-supervisor.svg" alt="" width="64" height="64">```
 adding px is not the correct format, by just adding 64 it is assumed its pixels already.


2. The way the 4 cards are positioned in a cross pattern,when using CSS Grid, it is not very intuitive how many rows and columns to make, because the side column visually look like they start in the middle of  grid cells. You solve this problem by giving each card 2 row cells.
I used a Grid of 3 columns and 4 rows to create the design.

Thank you for reading.
