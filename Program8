#include<stdio.h>
#include<conio.h>

char FT[5];
char FL[5];

void checkfirst(char x)
{
  int i=0;
    switch(x)
  {
    case 'a':
    FT[i]='a'; i++;
    break;

    case 'b':
    FT[i]='b';  i++;
    break;

    case 'e':
    FT[i]='e';  i++;
    break;

    case ')':
    FT[i]=')';  i++;
    break;

    case 'i':
    FT[i]='i';  i++;
    break;

    case '@':
    FT[i]='@';  i++;
    break;
   }
}



void checkfollow(char x)
{
  int i=0;
    switch(x)
  {
    case 'a':
    FT[i]='a'; i++;

    break;
    case 'b':
    FT[i]='b';  i++;

    break;
    case 'e':
    FT[i]='e';  i++;
    break;

    case 't':
    FL[i]='t';  i++;
    break;

    case 'i':
    FT[i]='i';  i++;
    break;

    case '@':
    FT[i]='@';  i++;
    break;
   }
}


void first(char y)
{ int i;
  checkfirst(y);
  for(i=0;i<2;i++)
  printf("%c", FT[i]);
}

void follow(char y)
{ int i;
  FL[0]='$';
  if(y=='e')
  first(y);

  checkfollow(y);
  for(i=0;i<2;i++)
  printf("%c", FL[i]);
}

  void main()
  {
  int i;
  char S1[]="iCtSS'";
  char S2[]="a";
  char s1[]="eS'";
  char s2[]="@";
  char C1[]="b";
  char X[]="tS";
  char t1,t2,e1,e2,c1,x;
  t1=S1[0];
  t2=S2[0];
  e1=s1[0];
  e2=s2[0];
  c1=C1[0];
  x=X[0];

  clrscr();
  printf("\nFIRST [S]: ");
  first(t1);
  first(t2);
  printf("\n\nFIRST [S']: ");
  first(e1);
  first(e2);
  printf("\n\nFIRST [C]: ");
  first(c1);

 printf("\n\nFOLLOW [S]: ");
 follow(e1);


 printf("\n\nFOLLOW [S']: ");
 follow(e1);

 printf("\n\nFOLLOW [C]: ");
 follow(x);


  getch();
 }
