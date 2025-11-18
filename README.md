# bee1101-number-problem
[main.c](https://github.com/user-attachments/files/23598640/main.c)
#include <stdio.h>
#include <stdlib.h>
#include <stdio.h>
int main(){
int m,n;
while(1){
    scanf("%d %d",&m,&n);
    if(m<=0 || n<=0)break;
    int temp;
    int sum=0;
    if(m>n){
        temp=m;
        m=n;
        n=temp;
    }
    for(int i=m;i<=n;i++){
        printf("%d ",i);
        sum+=i;
    }
    printf("Sum=%d\n",sum);
}
return 0;
}
