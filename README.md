Layouts, alignments & Arrangements


import packages needed for components
usually auto import

jo bhi red color mein ayega check for import packages
(right click -> show context action -> add import)

rows:- 		diff UI elements are layout( how they are arranged) 
		if we put elemnts inside a row ,they will be in a horizontal alignment

coloums:- 	similarly vertical.

	  	we can nest these in any way. the idea of subpages.

		Box -> all components align over others on the z-axis.

Modifier:-	decorate or configure UI elements/components
		change Layout appearance or behavior of composable ui elements

modifier
.padding- space around comp from adjacent ui element
.background- bg color change

syntax

row(modifier = modifier
		.fillmaxheight/fill max width/fill max size --- scope of row is handled
		.padding(20.dp)
		.background(Color.Red)
) {this is row scope}

order of modifier is important.

horizontal alignment aligns horizontally.


vertical arrangement arranges vertically



test and attach screenshots :- https://developer.android.com/develop/ui/compose/modifiers

Today’s Assignment:-
- Read Docs about Layout and Alignment in Jetpack. Try all the layout in Android Studio
- Practise all the Layouts:- (Row/Column/Box) with alignment and arrangement
- Push all the codes to git and notify me once done
