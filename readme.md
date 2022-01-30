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

            Private Static GImage ShopLabel = new GImage("media/images/ShopLabel.png");
            Private Static GImage CharacterLabel = new GImage("media/images/CharLabel.png");
            Private Static GImage LevelLabel = new GImage(GImage("media/images/LevelLabel.png");
            
            public void initializeObjects() {
            		ShopLabel.setSize(perfect x value size, perfect y value size);
            		ShopLabel.setLocation(x location under shop button, y location under shop button);
            		CharacterLabel.setSize(perfect x value size, perfect y value size);
            		CharacterLabel.setLocation(perfect x value size, perfect y value size);
            		LevelLabel.setSize(perfect x value size, perfect y value size);
            		LevelLabel.setLocation(perfect x value size, perfect y value size);
            }
					
}