# c-warehouse
It all starts now.
#include<stdio.h>
 main()
 {int w,s,l;
  for(w=1;w<1000;w++)//总数 
    {for(l=1,s=0;l<w/2;l++)//条件中，一半以后的数，没有完全数 
      if(!(w%l)) s=s+l;
      if(s==w) printf("%d是完全数",w); }
   
 }
