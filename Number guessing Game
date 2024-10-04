public class Main
{ 
    public static void main(String args[])
    {
      Random rand = new Random();
     
     
      Scanner scanner = new Scanner(System.in);
      
       int randomNumber = rand.nextInt(100) + 1;
       while(true)
       {
        System.out.println("Enter your guess(1-100):");
       
       int playerGuess = scanner.nextInt();
       if(playerGuess==randomNumber)
       {
           System.out.println("Delicious!you win!");
           break;
       }
       else if(randomNumber>playerGuess)
       {
          System.out.println("No!The number is higher.Guess again."); 
       }
       else
       {
           System.out.println("No!The number is lower.Guess again."); 
       } 
      }
    }
}
