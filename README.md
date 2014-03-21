MLP-adventure-game


//mlp adventure game. still in the works


import java.util.Scanner;


public class adventureMlp {
public static String name, askName, runGame;
public static int choice, twilight1, twilight2;
	public static void main(String[] args) 
	{
		askName();
		runGame();
	}

public static String askName()
	{
		System.out.println("What is your name?");
		Scanner userInput2 = new Scanner(System.in);
		name = userInput2.nextLine();
		return askName;
	}
	
	public static String runGame()
	{
		System.out.println("Which character of the main 6 would you like to play as? (remember to Capitalize)");
		System.out.println("1 Twilight ; 2 Rainbow Dash ; 3 Apple Jack ; 4 Pinkie Pie ; 5 Fluttershy ; or 6 Rarity?"); 
		Scanner userInput1 = new Scanner(System.in);
		choice = userInput1.nextInt();
		
			if (choice == 1)
			{
				System.out.println("You Chose Twilight!");
				System.out.println(" You wake up at the Libarary. Do you want to 1 go help AJ at Sweet Apple Acres or"
						+ " 2 Go help Pinkie Pie bake a cake for Fluttershy's birthday?");
								Scanner userInput3 = new Scanner(System.in);
								twilight1 = userInput3.nextInt();
								if(twilight1 == 1)
								{
									System.out.println("You head over to Sweet Apple Acres");
									System.out.println("You see Apple Bloom and head over to ask where AJ is.");
									System.out.println("You find out from Apple Bloom that AJ is in bed sick. You decide to ggo back home");
								}
								
								if(twilight1 == 2)
								{
									System.out.println("You head over to Sugar Cube Corner");
									System.out.println("You and Pinkie Pie spend 2 hours baking a cake for FlutterShy");
									System.out.println("Pinkie Pie lets you draw a bird on the cake with icing.");
									System.out.println("You decide to go help Rainbow Dash with the fireworks for the party.");
									System.out.println("Rainbow Dash sees you walking up and you two share greetings.");
									Scanner userInput4 = new Scanner(System.in);
									twilight2 = userInput4.nextInt();
											if (twilight2 ==1 )
											{
												System.out.println( "You shose sparklers. At the party, FlutterShy is over joyed with the quite, yet bright sparklers");
											}
											if (twilight2 == 2)
											{
												System.out.println("At the party, the fireworks start going off. ");
												System.out.println("At first, Fluttershy is scared, but then comes out and enjoys there beauty");
											}
								}
			}
			if (choice == 2)
			{
				System.out.println("You Chose Rainbow Dash!");
			}
			if (choice == 3)
			{
				System.out.println("You Chose Apple Jack!");
			}
			if (choice == 4)
			{
				System.out.println("You Chose Pinkie Pie!");
			}
			if (choice == 5)
			{
				System.out.println("You Chose FlutterShy!");
			}
			if (choice == 6)
			{
				System.out.println("You Chose Rarity! not the best choice");
			}
		return runGame;
	}
	
}
