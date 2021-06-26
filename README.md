//# FizzBuzz
//https://codingdojo.org/kata/FizzBuzz/



import java.util.stream.IntStream;

public class FizzBuzz 
{
    public static void main(String[] args) 
    {
      FizzBuzz(100);
    }
    private static void FizzBuzz(int num)
    {
        for (int i = 1; i<= 100; i++)
        {
            if(((i % 5) == 0) && ((i % 3) == 0))
                System.out.println("fizzBuzz");
            else if ((i % 5) == 0)
                System.out.println("buzz");
            else if ((i % 3) == 0)
                System.out.println("fizz");
            else 
                System.out.println(i);
        }
    }   
}







