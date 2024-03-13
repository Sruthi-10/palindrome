import java.util.*;
public class Main {
    public static void main(String[] args){
    Scanner sc = new Scanner(System.in);
    int n = sc.nextInt();
    int s=0,a;
    a=n;
    while(n>0){
        s=s*10 + n%10;
        n=n/10;
    }
    if(a==s)
    {
        System.out.println("Palindrome");
    }
    else{
        System.out.println("Not a Palindrome");
    }
        
    }
}
