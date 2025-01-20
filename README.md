# Operators-
import java.util.Scanner;

/**

*

* @author 1BSCCSA53

*/

public class OPERATORS {

/**

* @param args the command line arguments

*/

public static void main(String[] args) {

// TODO code application logic here

Scanner sc=new Scanner(System.in);

System.out.print("enter a first value");

int a=sc.nextInt();

System.out.print("enter a second value");

int b=sc.nextInt();

System.out.println("enter a third value");

int c=sc.nextInt();

System.out.println("ARITHIMETIC OPERATOR:");

System.out.println(" the value of a:"+a );

System.out.println("the value of b:"+b);

System.out.println("the value of c:"+c);

System.out.println("addition:"+(a+b));

System.out.println("subsraction:"+(a-b));

System.out.println("multiplication:"+(a*b));

System.out.println("division:"+(a/b));

System.out.println("modulus:"+(a%b));

System.out.println("RELATIONAL OPERATOR:");

if(a<b)

System.out.println(+a+"is lesser than"+b);

else

System.out.println(+a+"is not lesser than "+b);

if(a>b)

System.out.println(+a+"is greater than"+b);

else

System.out.println(+a+"is not greater than"+b);

if(a==b)
System.out.println(+a+"is equal to "+b);

if(a!=b)

System.out.println(+a+"is not equal to"+b);

System.out.println("LOGICAL OPERATOR:");

System.out.println("AND OPERATOR");

System.out.println((a>b)&&(a>c));

System.out.println("OR OPERATOR:");

System.out.println((a>b)||(a>c));

System.out.println("NOT OPERATOR");

System.out.println(!(a==b));

System.out.println("TERNARY OPERATOR");

System.out.println((a==c)?"it is equal ":"it is not equal");

}

}

OUTPUT

enter a first value2

enter a second value3

enter a third value

5

ARITHIMETIC OPERATOR:

the value of a:2

the value of b:3

the value of c:5

addition:5

subsraction:-1

multiplication:6

division:0

modulus:2

RELATIONAL OPERATOR:

2is lesser than3

2is not greater than3

2is not equal to3

LOGICAL OPERATOR:

AND OPERATOR
System.out.println(+a+"is equal to "+b);

if(a!=b)

System.out.println(+a+"is not equal to"+b);

System.out.println("LOGICAL OPERATOR:");

System.out.println("AND OPERATOR");

System.out.println((a>b)&&(a>c));

System.out.println("OR OPERATOR:");

System.out.println((a>b)||(a>c));

System.out.println("NOT OPERATOR");

System.out.println(!(a==b));

System.out.println("TERNARY OPERATOR");

System.out.println((a==c)?"it is equal ":"it is not equal");

}

}

OUTPUT

enter a first value2

enter a second value3

enter a third value

5

ARITHIMETIC OPERATOR:

the value of a:2

the value of b:3

the value of c:5

addition:5

subsraction:-1

multiplication:6

division:0

modulus:2

RELATIONAL OPERATOR:

2is lesser than3

2is not greater than3

2is not equal to3

LOGICAL OPERATOR:

AND OPERATOR
false

OR OPERATOR:

false

NOT OPERATOR

true

TERNARY OPERATOR

it is not equal

BUILD SUCCESSFUL (total time: 21 seconds)
