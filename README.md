# ansi2kr
asu ansi2kr  ANSI C to K&amp;R C converter for BDS C , MSX-C

Ver 1.3

Support OS: Windows,CP/M,MSX-DOS,MSX-DOS2
ANSI C source. (Support C Compiler: C++ Builder, BDS C/MSX-C with asu ansi2kr)

BDS C and MSX-C are subset K&amp;R C compilers.
asu ansi2kr add some ANSI C function to BDS C and MSX-C.


    #include <stdio.h>
    unsigned char sub(unsigned char a,int b)  
    {  
      return a + (unsigned char)b;  
    }  
    void main(void)  
    {  
      unsigned char c;  
      c = sub((unsigned char)'A',1);  
      printf("%c",c);  
    }

Convert for BDS C
      
    #include <stdio.h>
    char sub(a,b)char a;int b;  
    {  
      return a + b;  
    }  
    void main()  
    {  
      char c;  
      c = sub('A',1);  
      printf("%c",c);
    } 
