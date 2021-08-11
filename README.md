# 7.-CONSTANTS-AND-LITERALS-IN-C
#include <stdio.h>
int main() 
{
const int HEIGHT = 10;
 const int BASE = 5;
 const char NEWLINE = '\n';
 int area; 
 
 area = (HEIGHT * BASE)/2;
 printf("value of area : %d", area);
 printf("%c", NEWLINE);
 return 0;
}
