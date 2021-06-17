# conditional-statement
this contains the conditional statement of fooditems
#include<stdio.h>
main()
{
   printf("pick an item: \n1.pizza\n2.burger\n3.pasta\n4.french fries\n5.sandwich);
   int choice=0;
   scanf("%d",&choice);
   
   
   switch(choice)
   {
      case1:
         printf("you picked pizza.");
      case2:
         printf("you picked burger.");
      case3:
          printf("you picked pasta.");
      case4:
          printf("you picked french fries.");
      case5:
           printf("you picked sandwich.");
       default:printf("invalid choice");
     }
  }
