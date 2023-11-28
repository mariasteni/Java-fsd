# project 1
package assistproject;

public class TypeCasting {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("Implicit Type Casting");
		char a='A';
		System.out.println("Value of a: "+a);
		
		int b=a;
		System.out.println("Value of b: "+b);
		
		float c=a;
		System.out.println("Value of c: "+c);
		
		long d=a;
		System.out.println("Value of d: "+d);
		
		double e=a;
		System.out.println("Value of e: "+e);
		
				
		System.out.println("\n");
		
		System.out.println("Explicit Type Casting");
		//explicit conversion
		
		double x=45.5;
		int y=(int)x;
		System.out.println("Value of x: "+x);
		System.out.println("Value of y: "+y);
		
	}


	}

# project 2
package assistproject;

class Print {

int value1 = 100;
private int value2 = 400;

private void msg() {

	System.out.println("Hello java");
}
}

public class A {

public static void main(String args[]) {

	Print obj = new Print();
	System.out.println(obj.value2);// Compile Time error because of value declared as private and cannot be fetched
									// outside of class

	System.out.println(obj.value1); // since here value1 is accessible because of its declaration is default

	obj.msg();// Here we cpackage assistproject;



	}

}

