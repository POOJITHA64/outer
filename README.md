# outer_x
import java.util.*;
class outer 
{
    int outer_x;
    void test()
    {
        System.out.println("enter the outer_x value");
        Scanner k=new Scanner(System.in);
        outer_x=k.nextInt();
        inner o=new inner();
        o.display(); 
    }
}
class Main 
{
    void display()
    {
        System.out.println("the value of outer_x:"+outer_x);
    }
}
class innerclassDemo
{
    public static void main(String args[])
    {
        outer p=new outer();
        p.test();
    }
}
