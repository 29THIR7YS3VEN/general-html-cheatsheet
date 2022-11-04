# General HTML cheatsheet

### Basic Tags
- `<html>...</html>` Lets the browser know that this will be a HTML document.
- `<head>...</head>` Sets off everything that isn't displayed on the webpage, such as the title (which is displayed on the tab)
- `<body>...</body>` The visible portion of the webpage
- `<title>...</title>` The title of your document, which usually appears on the tab and not the page itself.
### Headers
- `<h1>...</h1>` The largest header
- `<h2>...</h2>` A smaller header
- `<h3>...</h3>` A smaller header
- `<h4>...</h4>` A smaller header
- `<h5>...</h5>` An even smaller header
- `<h6>...</h6>` A tiny header
- `<h7>...</h7>` The smallest header
### Text
- `<pre> </pre>`
Creates preformatted text
- `<b> </b>` or `<strong> </strong>`
Creates bold text
- `<i> </i>` or `<em> </em>` 
Creates italicized text
- `<code> </code>`
Used to define source code, usually monospace
- `<cite> </cite>`
Creates a citation, usually processed in italics
### Lists
- `<ul> </ul>`
Creates an unordered list
- `<ol start=?> </ol>`
Creates an ordered list (start=xx,
where xx is a counting number)
- `<li> </li>`
Encompasses each list item
- `<dl> </dl>`
Creates a definition list
- `<dt>`
 Precedes eachdefintion term
- `<dd>`
 Precedes eachdefintion
### Images
- `<img src="URL" />`
Adds image; it is a separate file located at the URL
- `<img src="URL" align=?>`
Aligns image left/right/center/bottom/top/middle (use CSS)
- `<img src="URL" border=?>`
Sets size of border surrounding image (use CSS)
- `<img src="URL" height=?>`
Sets height of image, in pixels
- `<img src="URL" width=?>`
Sets width of image, in pixels
- `<img src="URL" alt=?>`
Sets the alternate text for browsers that can't
process images (required by the ADA)
### Forms
- `<form> </form>`
Defines a form
- `<select multiple name=? size=?> </select>`
Creates a scrolling menu. Size sets the number of
menu items visible before user needs to scroll.
- `<select name=?> </select>`
Creates a pulldown menu
- `<option>`
Sets off each menu item
- `<textarea name=? cols="x" rows="y"></textarea>`
Creates a text box area. Columns set the width;
rows set the height.
- `<input type="checkbox" name=? value=?>`
Creates a checkbox.
- `<input type="checkbox" name=? value=? checked>`
Creates a checkbox which is pre-checked.
- `<input type="radio" name=? value=?>`
Creates a radio button.
- `<input type="radio" name=? value=? checked>`
Creates a radio button which is pre-checked.
- `<input type="text" name=? size=?>`
Creates a one-line text area. Size sets length, in
characters.
- `<input type="submit" value=?>`
Creates a submit button. Value sets the text in the
submit button.
- `<input type="image" name=? src=? border=? alt=?>`
Creates a submit button using an image.
- `<input type="reset">`
Creates a reset button
- `<input type="email" name=?>`
 Sets a single-line textbox for email addresses
- `<input type="url" name=?>`
 Sets a single-line textbox for URLs
- `<input type="number" name=?>`
 Sets a single-line textbox for a number
- `<input type="range" name=?>`
 Sets a single-line text box for a range of numbers
- `<input type="date/month/week/time" name=?>`
 Sets a single-line text box with a calendar
 showing the date/month/week/time
- `<input type="search" name=?>`
 Sets a single-line text box for searching
- `<input type="color" name=?>`
 Sets a single-line text box for picking a color 
 
### Tables 
- `<table> </table>`
Creates a table
- `<tr> </tr>`
Sets off each row in a table
- `<td> </td>`
Sets off each cell in a row
- `<th> </th>`
Sets off the table header (a normal cell with bold,
centered text)
- `<table border=?>`
Sets the width of the border around table cells
- `<table cellspacing=?>`
Sets amount of space between table cells
- `<table cellpadding=?>`
Sets amount of space between a cell's border and
its contents
- `<table width=?>`
Sets width of the table in pixels or as a percentage
- `<tr align=?>`
Sets alignment for cells within the row
(left/center/right)
- `<td align=?>`
Sets alignment for cells (left/center/right)
- `<tr valign=?>`
Sets vertical alignment for cells within the row
(top/middle/bottom)
- `<td valign=?>`
Sets vertical alignment for cell (top/middle/bottom)
- `<td rowspan=?>`
Sets number of rows a cell should span (default=1)
- `<td colspan=?>`
Sets number of columns a cell should span
- `<td nowrap>`
Prevents lines within a cell from being broken to fit


