## I am using a past websabe "How to make a Proper Pot of Tea" 
-------------------------------------------------
Index.html : Techniques Used & Changes
-------------------------------------------------

1. Sizing  
   - OLD: Some elements did not have consistent heights, which made the layout uneven.  
   - NEW: I set fixed heights on sections like `.materials` and `.instructions` (example: height: 400px).  
   This makes each section more uniform and creates a cleaner presentation. 

2. Overflow  
   - OLD: Text inside `.info-cell` and `.box` would overflow and stretch the layout.  
   - NEW: I added `overflow-y: auto` to `.info-cell` and `.box-text`.  
   Now long text scrolls inside its container instead of breaking the layout.

3. Border  
   - OLD: Borders were minimal or missing, especially in the tea table and card sections.  
   - NEW: I kept the table borders but made them visually cleaner and more consistent.  
   Borders now help organize rows and improve readability.

4. Margin  
   - OLD: Several sections sat too close to each other.  
   - NEW: I added consistent `margin: 17px 0` and `margin: auto` spacing to create separation.  
   This improves flow and reduces visual clutter.

5. Padding  
   - OLD: Some elements had uneven padding, making text feel too close the edges.  
   - NEW: I standardized padding (ex: 15px–30px) inside `.box`, `.instructions`, `.info-cell`, and `.tea-leaves-card`.  
   Padding improves readability and creates a more polished, finished look. 

6. Display (inline-block, flex, grid)  
   - OLD: Display types were used but not fully optimized, and some flex sections overlapped or wrapped awkwardly.  
   - NEW:  
       • Navigation uses `display: inline-block` for spacing.  
       • `.section` and `.instruction-box` use `flex` for responsive two-column layouts.  
       • `.materials` uses `grid` for 2-column alignment.  
   These display choices make the layout cleaner and easier to control.

7. Positioning  
   - OLD: The navigation was positioned with float but lacked spacing.  
   - NEW: I kept `float: right` but improved padding to better align the title and navigation bar.  

-------------------------------------------------
GOALS 
-------------------------------------------------

- Improved readability with scrolling text areas
- Cleaner layout with consistent spacing (margin + padding)
- Better control over element alignment using flex and grid
- More stable layout due to fixed heights in key areas
- External CSS is now fully used (no inline CSS except video sizing)
- Visual organization is improved, especially in materials and instruction sets

Select at least 6 of the following techniques to implement:

    Sizing – Control the width and height of elements on the page.
    Overflow – Manage how content is displayed when it exceeds the element’s boundaries.
    Border – Define and style borders around elements for emphasis or separation.
    Margin – Adjust the space outside an element, creating separation from other elements.
    Padding – Set the space inside an element, between its content and border.
    Display: Inline / Inline-block – Specify how elements are displayed in relation to others.
    Dropdown – Create a dropdown menu for navigation or content organization.
    Position – Control the placement of elements with properties like absolute, relative, or fixed.