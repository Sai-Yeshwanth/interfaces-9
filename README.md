Error!!!! only public or abstract are accepted

private interface A
{
	int a=5;
	void display();
}
class C implements A
{
	public void display()
	{
		System.out.println("Im from interface A and value is:" + a);
	}
}
class Jala 
{
	public void show()
	{
		System.out.println("Im definition of abstact method");
	}
	public static void main(String[] args){ 
			 C c = new C();
			 c.display();
		
	}
}

