# swapping
swapping sample program


class swapping
{
int a=4,b=3,c=9,d=1;
void display()
{
int temp=a;
a=b;
b=c;
c=d;
d=temp;
System.out.println("a is:"+a+"b is"+b);
System.out.println(c);
System.out.println(d);

}
public static void main(String[]args)
{
swapping a=new swapping();
a.display();
}
}
