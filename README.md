# HeartBreakKidGame_Using_C
1.1	Introduction 

The project on the Heart breaking kid game is a simple and small basic level project for entertaining purpose. 
In the Heart breaking game, the two small hearts falls at particular time by other three ball hearts, user have to avoid those small hearts to have a good score, the ball heart has to be hit by the user for points by an small triangle have a power to hit by the arrow, if it falls , then the chances of lives decreases of the user. There are only two lives given to the user. And for presenting the final score we have used the end command function this will appear in the final score of the game.for hitting the ball hearts we have different type of function like hitx[bct], we have used settextyle() and setcolor() functions for giving different colors to the ball hearts. For giving the image of heart inside the ball we have used and putimage(); by using flags. These are all main objects or a functions that are been used  most of places to design this project. 
In this Heart breaking kid game , using procedure oriented method to design and  programming concept like Switch case , call by reference , library function like randomize() this function is used for the main controls of the game, random() for giving the speed of the motion of heart balls.
This project is made for fun and entertainment for users.
This project is on C++ platform which is coded in TurboC++ IDE.

2	CG Concepts

2.1	Output primitives used 

The output primitives are the simple geometric functions that are used to generate various computer graphics required by the user.
	Line – Line function is used to draw the line on the screen.
setlinestyle(0,0,THICK_WIDTH); line(5,yend-5,20,yend-5); line(xend,285,getmaxx(),285 these all are used to show the arrow whle firing and use to make tabeles in the game.
	Rectangle – Rectangle function is used to draw the rectangle on the screen.
rectangle(1,1,xend,getmaxy()); these functions are used to make boxes for getting the view of the particular information at particular part and other side to build the particular farame of the game performace.
	Circle – Circle function is used to draw the circle on the screen.
circle(r+5,r+5,r); this function is used to make the balls of particular size so that the image of heart can be situated inside balls.
 
2.2	Graphics functions used

•	Setcolor()
Setcolor is used to set color of the objects, fonts and the tables of the whole game.
setcolor(RED);//this function is used to set the color of objects ,texts,etc.in this project.
•	Settextstyle()
Settextstyle sets the current text characteristics like font , direction and size.
settextstyle(0,0,2);//it used for the size of the text to show in the game.
•	Outtextxy()
Outtextxy function is used to print the text on the screen in graphics mode.
outtextxy(getmaxx()/2-130,getmaxy()/2-100,msg);//this used for the maximum space outside the text on the screen according to the co-ordinates located.
•	Getmaxx()
Getmaxx returns the maximum x co-ordinate on the screen.

•	Getmaxy()
Getmaxy returns the maximum y co-ordinate on the screen.
(getmaxx()/2-100,getmaxy()/2-50,"Heart Break Kid Game");//this function is used the maximum size of the statement according to the co-ordinates situated.

•	Setlinestyle()
Setlinestyle function is used to set the current line style , width and pattern.
setlinestyle(0,0,THICK_WIDTH);//it is used to adjust the width of the line.


•	Setfillstyle()
Setfillstyle is used to set the colour and style to be filled in the object using the flood fill method.
setfillstyle(10,12);//it is used to fill the color of the object

•	Malloc()
Malloc function is used to assign a specified amount of memory for an array to be created.
malloc(size3);//the function assigned the size of an object to be created.

•	getimage()
this function is used to get the image of the ball and imagesize() function is used to maintain the size of an object.

•	gotoxy()
It is used to place the cursor at the desired location on the screen gotoxy(55,12);

•	Hitflag[]
hitflag[bct] = 1;under this many of the hit function is used to design the game.

•	Gettime()
It returns the current time.
(msg,"   Current Time:%2d:%02d:%02d",t.ti_hour, t.ti_min,t.ti_sec);//This shows the current time of the game that the user is palyed for a particular time slot.

4       Conclusion : 

In this project , used procedure oriented method to design the graphical parts of the game.The project has many graphical concepts to design this game.
Also, used programming concept like switch case , call by reference , library function like randomize() this function is used for the main controls of the game, random() for giving the speed of the motion of heart balls. There are only two lives given to the user. And for presenting the final score we have used the end command function this will appear in the final score of the game.for hitting the ball hearts we have different type of function like hitx[];we have used settextyle and setcolor for giving a different colors to the ball hearts. For giving the image of heart inside the ball we have iused putimage(); function and putimage(); by using flags.These are all main objects or a  graphical functions that are been used  most of palces to design this project. 
This project is made for fun and entertainment for the users.


