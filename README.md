<div align="center">

## Multiplication Table


</div>

### Description

This code will accept values from the user and them display a multiplication table. If you like this code please vote for it. You can reach me at jakerpomperada@yahoo.com. My Complete home address is Jake Rodriguez Pomperada Purok Pag-asa, Barangay Alijis 6100 Bacolod City, Negros Occidental Philippines. Happy Programming and God Bless :-D
 
### More Info
 
It will ask the number of columns and rows so that it will generate a multiplication table from the given values of the user.

Displays Multiplication Table.

There is no side effects of using this code.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jake Rodriguez Pomperada](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jake-rodriguez-pomperada.md)
**Level**          |Advanced
**User Rating**    |4.7 (14 globes from 3 users)
**Compatibility**  |C, C\+\+ \(general\), Microsoft Visual C\+\+, Borland C\+\+
**Category**       |[Complete Applications](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/complete-applications__3-7.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jake-rodriguez-pomperada-multiplication-table__3-11893/archive/master.zip)





### Source Code

```
/* Program : Multiplication Table */
/* Author  : Mr. Jake Rodriguez Pomperada */
/* Date   : December 27, 2007 9:26 PM */
/* Language : C */
/* Tool   : Turbo C 2.0 */
#include <stdio.h>
#include <conio.h>
main ()
{
 int  i=0, j=0;
 int rows=0, cols=0;
  clrscr();
   printf("Enter No. of Rows  : ");
   scanf("%d",&rows);
   printf("Enter No. of Columns : ");
   scanf("%d",&cols);
 printf("\n\n");
 printf("\tTHE MULTIPLICATION TABLE ");
 printf("\n\n");
 for (i = 1; i <= rows; i++)
 {
  for (j = 1; j <= cols; j++)
    printf ("%4d ", i*j);
  printf ("\n");
 }
 getche();
} /* End of Code */
```

