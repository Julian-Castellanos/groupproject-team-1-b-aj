##Overview
The feature that I will be adding is adding explanations as to what everything does. I will be doing this by adding text
on the three buttons that will take you to character selection, the shop, and levels. I will first add a text in a 
button that says test to see if it worked and commit it, then change it and add a description and do the same for the 
remaining buttons. 

Also to be able to run this open the group-project/src folder then open projects and click on 
MainMenu.java and run the program. This is the only way to run the program

##PseudoCode
//Code will be added in MainMenuGraphics.java next to all the GImage's and Grect's

public class MainMenuGraphics extends GraphicsPane implements ActionListener {

            GLabel ShopLabel = new;
				GLabel("You can buy cards here", position under shop button, position under shop button);
				ShopLabel.setColor(Color.GREEN);
				GLabel LevelLabel = new;
				GLabel("Defeat enemies gain coins!", position under Level button, position under label button);
				LevelLabel.setColor(Color.GREEN);
				GLabel CharacterLabel = new;
				GLabel("Select your character", position under char select, position under char select button);
				CharacterLabel.setColor(Color.GREEN);
					
}