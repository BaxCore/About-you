# About-you
this program allows you enter information about you 
#include <stdio.h>
/*This program asks a user to type the following;
1.the given name
2.the sur name
3.the home village
4.the age */
int main()
{   printf("ENTER INFORMATION AS REQUSTED");

      //data declaration
      char name1[10], name2[10], village[10];
      int age[3];

    //given name
      printf("\n\nType in your given name:\t");
      scanf("%s",&name1);

    //surname
      printf("\n\nType in your surname:\t");
      scanf("%s",&name2);

    //age
      printf("\n\nHow old are you:\t");
      scanf("%d",&age);

    //village
      printf("\n\nType in the name of your village:\t");
      scanf("%s",&village);

printf("\n\n");
    return 0;
}
