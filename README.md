TicTacToe
=========



import javax.swing.JOptionPane;

public class TicTacToe 

{

  
  public static void main(String[] args) 
  {
  	
  	boolean bPlaying = true;
  
  	String sBoard = "";
  	String Cell2 = "2";
  	String Cell3 = "3";
  	String Cell4 = "4";
  	String Cell5 = "5";
  	String Cell6 = "6";
  	String Cell7 = "7";
  	String Cell8 = "8";
  	String Cell9 = "9";
  	String Cell1 = "1";
  	String userMove;
  	boolean inValidMove = true;
  	
  	do
  	{
  	inValidMove = true;
  		do 
  		{
  		
  		
  		
  		sBoard = Cell1 + " | " + Cell2 + " | " + Cell3 + "\n";
  		sBoard = sBoard + "---|---|---" + "\n";
  		sBoard = sBoard + Cell4 + " | " + Cell5 + " | " + Cell6 + "\n";
  		sBoard = sBoard + "---|---|---" + "\n";
  		sBoard = sBoard + Cell7 + " | " + Cell8 + " | " + Cell9 + "\n";
  		sBoard = sBoard + "Enter a number (1-9) to make your move:";
  		 userMove = JOptionPane.showInputDialog(null, sBoard);
  		 
  		 	if (userMove.equalsIgnoreCase("1")) 
  		 	{
  		 			if ( !Cell1.equals("1"))
  					 {
  				 		JOptionPane.showMessageDialog(null, "Sorry this number already taken. Please try again");
  					 }
  			 else
  				 	Cell1= "X";
  		 			inValidMove = false;
  		 	}
  		 	
  		 	else if (userMove.equalsIgnoreCase("2")) 
  		 	
  		 		{
  		 			if ( !Cell2.equals("2"))
  		 			{
  		 				JOptionPane.showMessageDialog(null, "Sorry this number already taken. Please try again");
  		 			}
  		 		
  		 			else
  		 			Cell2= "X";
  		 			inValidMove = false;
  		 		}
  				
  		 	else if (userMove.equalsIgnoreCase("3")) 
  		 		{
  		 			if ( !Cell3.equals("3"))
  		 			{
  		 				JOptionPane.showMessageDialog(null, "Sorry this number already taken. Please try again");
  		 			}
  	 		
  		 			else
  		 			Cell3= "X";
  		 			inValidMove = false;
  		 		}
  		 	else if (userMove.equalsIgnoreCase("4")) 
  		 		{
  		 			if ( !Cell4.equals("4"))
  		 			{
  		 				JOptionPane.showMessageDialog(null, "Sorry this number already taken. Please try again");
  		 			}
  	 		
  		 			else
  		 			Cell4= "X";
  		 			inValidMove = false;
  		 		}
  		 	else if (userMove.equalsIgnoreCase("5")) 
  		 		{
  		 			if ( !Cell5.equals("5"))
  		 			{
  		 				JOptionPane.showMessageDialog(null, "Sorry this number already taken. Please try again");
  		 			}
  	 		
  		 			else
  		 			Cell5= "X";
  		 			inValidMove = false;
  		 		}
  		 	else if (userMove.equalsIgnoreCase("6")) 
  		 		{
  		 			if ( !Cell6.equals("6"))
  		 			{
  		 				JOptionPane.showMessageDialog(null, "Sorry this number already taken. Please try again");
  		 			}
  	 		
  		 			else
  		 			Cell6= "X";
  		 			inValidMove = false;
  		 		}
  		 	else if (userMove.equalsIgnoreCase("7")) 
  		 		{
  		 			if ( !Cell7.equals("7"))
  		 			{
  		 				JOptionPane.showMessageDialog(null, "Sorry this number already taken. Please try again");
  		 			}
  	 		
  		 			else
  		 			Cell7= "X";
  		 			inValidMove = false;
  		 		}
  		 	else if (userMove.equalsIgnoreCase("8")) 
  		 		{
  		 			if ( !Cell8.equals("8"))
  		 			{
  		 				JOptionPane.showMessageDialog(null, "Sorry this number already taken. Please try again");
  		 			}
  		 			
  		 			else
  		 			Cell8= "X";
  		 			inValidMove = false;
  		 		}
  		 	else if (userMove.equalsIgnoreCase("9")) 
  		 		{
  		 			if ( !Cell9.equals("9"))
  		 			{
  		 				JOptionPane.showMessageDialog(null, "Sorry this number already taken. Please try again");
  		 			}
  	 		
  		 			else
  		 			Cell9= "X";
  		 			inValidMove = false;
  		 		}
  		 	
  		}
  		
  		while (inValidMove = true);
  		
  		
  	}
  	
  		while (bPlaying);
  	
  
  }
  
}
  


