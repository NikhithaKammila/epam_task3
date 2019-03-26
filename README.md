# epam_task3
epam third assignment
import java.util.*;
 
class Rod_Cutting {
    
Scanner sc=new Scanner(System.in);
int n=sc.nextInt();
while(n>0)
{
    int h=sc.nextInt();
    int c=0;
    int i=3;
    while(i<=h)
    {
        c+=1;
        i=2*i+1;
    }
    n--;
    System.out.println(c);
}
 
}
}
