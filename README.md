# Parameterized_constructor
class Test16
{
int z;
  Test16(int a,int b)
{
 int x=a;
  int y=b;
  z=x+y;
}
void disp()
{
 System.out.println("The value is:"+z);
}
public static void main(String args[])
{
  Test16 obj=new Test16(25,15);
  obj.disp();
}
}

