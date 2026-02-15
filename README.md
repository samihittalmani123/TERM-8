#include <stdio.h> 
int main() 
{ 
FILE *fp1, *fp2, *fopen(); 
char c; 
int i, cnt=49; 
fp1= fopen(“/root/Desktop/input.txt”,”r”); 
fp2=fopen((“/root/Desktop/output.txt”,”w”); 
if(fp1==NULL) 
{ 
printf(“cannot open input.txt\n”); 
exit(1); 
} 
else 
{ 
c=getc(fp1); 
while(c!=EOF) 
{ 
putc(cnt++,fp2); 
fputs(“192.168.1.1 , 192168.1.2”,fp2); 
for(i=0;i<5;i++) 
{ 
} 
putc(c,fp2); 
c=getc(fp1); 
putc(10,fp2) 
} 
printf(“Frames generated in output.txt File”); 
fclose(fp1); 
fclose(fp2); 
} 
return 0; 
} 
