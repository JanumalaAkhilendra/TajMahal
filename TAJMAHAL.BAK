#include<iostream.h>
#include<graphics.h>
#include<conio.h>
#include<dos.h>
#include<stdlib.h>
#include<stdio.h>
#include<process.h>

void main()
{

clrscr();

 int gd=DETECT,gm,errorcode;
 initgraph(&gd,&gm ,"../bgi");


  errorcode = graphresult();
if (errorcode != grOk)  /* an error occurred */
{
   printf("Graphics error: %s\n", grapherrormsg(errorcode));
   printf("Press any key to halt:");
   getch();
   exit(1);
 }

int a=50;

 line(0,300+a,700,300+a);// BASE LINE


 rectangle(225,100+a,375,300+a);

   rectangle(235,110+a,365,300+a);
     ellipse(300,280+a,0,90,35,45);
       ellipse(300,280+a,90,180,35,45);
	 line(265,300+a,265,270+a);
	   line(335,300+a,335,270+a);



 line(235,200+a,365,200+a);
   ellipse(300,175+a,0,90,35,45);
     ellipse(300,175+a,90,180,35,45);
       line(265,130+a,335,130+a);
	  line(265,200+a,265,130+a);
	     line(335,200+a,335,130+a);
int x=5;
// left pillar
sector(42,80,0,180,2,12);
line(70,300+a,55,50+a);

setcolor(LIGHTBLUE);
  ellipse(42,100+a,0,180,15,7);
    ellipse(42,90+x+a,320,230,25,7);
      ellipse(42,90+a,340,210,25,7);

setcolor(LIGHTBLUE);
  ellipse(42,170+a,0,180,20,7);
    ellipse(42,160+x+a,320,230,30,7);
      ellipse(42,160+a,340,210,30,7);

setcolor(LIGHTBLUE);
  ellipse(42,250+a,0,180,25,7);
    ellipse(42,240+x+a,320,230,35,7);
      ellipse(42,240+a,340,210,35,7);

setcolor(WHITE);
  line(15,300+a,30,50+a);
    line(55,50+a,30,50+a);

    setcolor(LIGHTBLUE);
     ellipse(42,45+a,330,210,17,12);

//right pillar
sector(560,80,0,180,2,12);
line(553-x,50+a,578-x,50+a);
  setcolor(LIGHTBLUE);
    ellipse(565-x,100+a,0,180,15,7);
      ellipse(565-x,90+x+a,320,230,25,7);
	ellipse(565-x,90+a,340,210,25,7);

   setcolor(LIGHTBLUE);
    ellipse(565-x,170+a,0,180,20,7);
      ellipse(565-x,160+x+a,320,230,30,7);
	ellipse(565-x,160+a,340,210,30,7);

  setcolor(LIGHTBLUE);
    ellipse(565-x,250+a,0,180,25,7);
      ellipse(565-x,240+x+a,320,230,35,7);
	ellipse(565-x,240+a,340,210,35,7);
  setcolor(WHITE);
    line(543-x,300+a,553-x,50+a);
      line(593-x,300+a,578-x,50+a);



      setcolor(LIGHTBLUE);
	ellipse(565-x,45+a,330,210,17,12);


//side rooms
setcolor(LIGHTBLUE);
ellipse(187,120+a,340,200,25,20); // tomb of side room



line(162,127+a,212,127+a);
rectangle(172,127+a,202,150+a);
rectangle(167,127+a,207,150+a);
setfillstyle(RED,23);
sector(187,100-x+a,0,180,2,12);
//windows of side rooms
    setcolor(WHITE);
    sector(187,200+a,0,180,15,30);
    line(160,200+a,215,200+a);
       setcolor(WHITE);
       sector(187,250+a,0,180,15,30);
       line(160,250+a,215,250+a);
	  setcolor(WHITE);
	  sector(187,300+a,0,180,15,30);

rectangle(150,150+a,225,300+a);
   line(150,150+a,110,170+a);
      line(110,170+a,110,300+a);
rectangle(160,160+a,215,300+a);

   setcolor(LIGHTBLUE);
   line(140,165+a,120,175+a);    //hori
      line(140,197+x+a,120,207+x+a);
	 line(140,165+a,140,300+a);
	    line(120,175+a,120,300+a);
	       line(120,260+a,140,250+a);

setcolor(LIGHTBLUE);
ellipse(412,120+a,340,200,25,20);//tomb of side room


line(387,127+a,437,127+a);
rectangle(397,127+a,427,150+a);
 rectangle(392,127+a,432,150+a);
   setcolor(WHITE);
    sector(412,100-x+a,0,180,2,12);
     setcolor(WHITE);
      sector(412,200+a,0,180,15,30);
	line(385,200+a,440,200+a);
	 setcolor(WHITE);
	  sector(412,250+a,0,180,15,30);
	    line(385,250+a,440,250+a);
	      setcolor(WHITE);
		sector(412,300+a,0,180,15,30);


rectangle(385,160+a,440,300+a);
 rectangle(375,150+a,450,300+a);
  line(450,150+a,490,170+a);
     line(490,170+a,490,300+a);
  setcolor(LIGHTBLUE);
   line(460,250+a,480,260+a);
      line(460,165+a,480,175+a);            //hori
	line(460,197+x+a,480,207+x+a);
	   line(460,165+a,460,300+a);  //vertical
	    line(480,175+a,480,300+a);
//dom construction
setcolor(LIGHTBLUE);
ellipse(300,75+a,330,210,80,50);
 setfillstyle(RED,23);
 sector(300,5+a,250,290,12,20);
//moon

arc(100,50,57,300,25);
arc(120,50,113,246,25);



getch();

}


