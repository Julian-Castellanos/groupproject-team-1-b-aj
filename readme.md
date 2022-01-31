##Overview
The feature that I will be adding is adding explanations as to what everything does. I will be doing this by adding text
on the three buttons that will take you to character selection, the shop, and levels. I will first add a text in a 
button that says test to see if it worked and commit it, then change it and add a description and do the same for the 
remaining buttons. 

Also to be able to run this open the group-project/src folder then open projects and click on 
MainMenu.java or MainMenuGraphics.java and run the program. This is the only way to run the program

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
            @Override
	         public void showContents() {
	         		program.add(ShopLabel);
	         		program.add(CharacterLabel);
	         		program.add(LevelLabel);
	         }
	         @Override
	         public void hideContents() {
	         		program.remove(ShopLabel);
	         		program.remove(CharacterLabel);
	         		program.remove(LevelLabel);
	         }					
}

##Last Section
In order to demonstrate that the feature has been implemented you can run the program as told how to in the overview section and 
and look towards the bottom of each button (the play, shop, and char select buttons). There you will see my feature saying what everything does. You can also see that I implemented this by looking in MainMenuGraphics.java in the public class MainMenuGraphics, initializeObjects()
function, and the showContents() and hideContents() functions. Buttons still work to take you to other sections of this project and you can tell because it'll make a noise and highlight the button outline blue when hovering over it.