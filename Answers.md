AllegiantAir-Quiz
=================
3.1 The Questions

    1) What industry blogs and resources do you follow to keep your skills up?
    - I follow 
    
    2) What tools do you use to develop software? Please provide your reasoning for each one.
    -
    3) What excites or interets you about coding?
    4) If you could master one technology this year; what would it be?
    5) What is object-oriented programming (OOP)?
    6) Explain test driven development (TDD).
    7) What do you use to test your applications?
    8) Explain the strategy pattern. Give a real world example.
    9) Explain the decorator pattern. Give a real world example.
    10) What is functional programming?

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
    
    
    
    
    
    
    
