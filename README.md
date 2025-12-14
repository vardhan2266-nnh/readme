### two sum 
#include <stdio.h>
int main()
{
    char line [100];
    int i;
    printf("enter line of text\n");
    fgets(line,sizeof(line),stdin);
    printf("%s",line);
    for(i=0;line[i]!='\0';i++)
    {
       line[i]=to lower(line[i]);
       if(line[i]=='a'!!line[i]=='e'!!line[i]=='i'!!line[i]=='0'!!line[i]=='u')
       vowels++;
       else
       if(line[i]>='0' && line[i]<='2')
       consonents++;
       else
       if(line[0>=0 && line[0]<=9)
       digits++;
    }
    printf("vowels=%d",vowels);
    printf("consonents=%d",consonents);
    printf("digits=%d\n",digits);
    return 0;
} 
