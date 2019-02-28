# CSPC-439-Project-1-
CSPC-439 Project 1 (team: Low Effort Group) 
Members: Bennett, Kim 

Kim-Lan Hoang
CWID:895005478


Intro:
Cella-rule-45 algorithm:
	The 1st array is created, using 30 cells with 1 colored cell in the middle. 4 Variable array is then created,
	containing specific cell numbers that correspond to what next row cell should be. After the 1st row is drawn,
	it copies itself to temporary array while creating a new one. In for loop, it puts 3 cells into a array set.
	That array set will compared itself to the other 4 variable array set to find a match. The cell being copied
	to starts from the 2nd cell to the 2nd to last cell. For example, on the currently selected cell, it gets the
 	cell number before, on, and after its own location.

	When it finds a match in the array set, the next row cell below the one selected will be set to 1, which indicate
	that cell will be colored. If no set match, the cell will be set to 0, which mean it will be blank. After 2nd to
	29th cell has been colored, the temporary array will store into the default array and then the next row will be drawn.
	The cycle will repeat for the total of 29 sets, exluding the 1st row.





Content:
README.txt
js-1.html
draw-stuff.js
styles.css

Setup:
Extract the zip file, and locate the file 'js-1.html' in the folder 'Js'. Drag the file onto the web browser.