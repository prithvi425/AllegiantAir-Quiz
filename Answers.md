AllegiantAir-Quiz
=================
3.1 The Questions

    1) What industry blogs and resources do you follow to keep your skills up?
    
    - I follow Spring.io block for spring related, stackOverFlow, some github profiles and some other Java related blogs
    
    2) What tools do you use to develop software? Please provide your reasoning for each one ?
    
    - Eclipse (Kepler) - For programming
      Spring 3.0  - Annotation based controllers
      Maven - software project management and comprehension.
      JRebel - Automatic deployment locally
      Hibernate - framework used for connection between java objects and dB r
      Oracle SQL Developer - for dB 
       And many more
      
    
    3) What excites or interets you about coding?
    - Challenge & Problem Solving. 
    
    4) If you could master one technology this year; what would it be?
    - Due to some enhancement in our application i started learning new technology JSF 2.0 for making the application UI     design look rich. This year i got good command on JSF 2.o
    
    5) What is object-oriented programming (OOP)?
    - A programming language which follows Inheritance & Abstraction. It revolves around object rather than actions and     data rather than logic. MOre centric towards Ojbects.
    
    6) Explain test driven development (TDD).
    - Test Driven Development is a software development approach in which a test is written before writing the code.        Once the new code passes the test, it is refactored to an acceptable standard. It makes sure that the writtern code     is throughly unit tested.
    
        
    7) What do you use to test your applications?
    - We use Junit 4.10 version and mockito 1.8.5 version for the application
    
    8) Explain the strategy pattern. Give a real world example.
    - This pattern defines a family of algorithms, encapsulation & make them interchangable. This pattern provide               interface and number of implementation for that interface where each implementation performs some function and          which can be totally replaced by other implementation which are independent of each other and enclosed in a         design
        
    A good example is Credit card purchase.
    
    9) Explain the decorator pattern. Give a real world example.
    - Decorator pattern are used to extend or modify the behaviour of an instance at runtime.
    
    A good eample is Icecream for decorator design pattern. You create a basic icecream and then add toppings to it as      you prefer. The added toppings change the taste of the basic icecream. You can add as many topping as you want. 
    
    10) What is functional programming?
    -

3.2 Show your skills

    1) Write a program that prints the numbers from 1 to 100. But for multiples of three print "Fizz" instead of the number and for multiples of five print "Buzz." For numbers which are multiples of both three and five print "FizzBuzz."
    
    
      public class ProgramOneTest {
      	public void count() {
      		for (int n = 1; n <= 100; n++) {
      			if (n % 3 == 0)
      				System.out.println("Fizz");
      			else if (n % 5 == 0)
      				System.out.println("Buzz");
      			else if (n % 15 == 0)
      				System.out.println("FizzBuzz");
      			else
      				System.out.println(n);
      		}
      	}
      
      	public static void main(String[] args) {
      		ProgramOneTest p1 = new ProgramOneTest();
      		p1.count();
      	}
      }

    2)Write a function that takes a string as an argument and returns the same string, but with each character separated by a space. If the string contains a white space character then return [s] in its place.
    
    
      public class ProgramTwoTest {
      
      	public void split(String arg) {
      		char[] arr = arg.toCharArray();
      		for (char s : arr)
      			if (s == ' ') {
      				System.out.print("[s]");
      			} else {
      				System.out.print(s + " ");
      			}
      	}
      
      	public static void main(String args[]) {
      		ProgramTwoTest p2 = new ProgramTwoTest();
      		p2.split("TEST");
      	}
      
      }
    
    
    
    
    
    
    
