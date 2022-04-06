# Rock_Paper_Scissor
java code game of Rock ,Paper and  scissor

import java.util.*;

public class rock

{
	public static void main(String args[])
  
	{
  
		int i=1;
    
		while(i<=5)
    
		{
    
			System.out.println("1.rock \n2.paper \n3.scissors");
      
			System.out.println("Enter your choice:");
      
			Scanner sc= new Scanner(System.in);
      
			i=sc.nextInt();
      
			Random gen=new Random();
      
			int c = gen.nextInt(3)+1;
      
			if (i==1)
      
			{
      
				System.out.println("Rock");
        
			}	
      
			else if(i==2)
      
			{
      
					System.out.println("paper");
          
			}
      
			else if(i==3)
      
			{
      
				System.out.println("scissor");
        
			}
      
			else
      
			{
				System.out.println("invalid choice");
			}

			if (c==1)
      
			{
				System.out.println("Rock");
			}	
			else if(c==2)
			{
				System.out.println("paper");
			}
			else if(c==3)
      
			{
				System.out.println("scissor");
			}
			else
      
			{
				System.out.println("invalid choice");
			}

			if(i==c)
      
			{
				System.out.println("Draw Match");
			}
      
			else if(i==1 &&c==3|| i==2 &&c==1 ||i==3 && c==2)
      
			{
				System.out.println("You Won the Game");
			}
      
			else if(c==1 &&i==3|| c==2 &&i==1 ||c==3 && i==2)
      
			{
				System.out.println("Computer Won the Game");
			}
      
		i++;
    
		}
    
	}	
	
}
