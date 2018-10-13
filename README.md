//Still Unfinished in some parts
//I also don't know much i'm new to java

package gameuno;

import java.util.Scanner;
import java.text.*;

public class GameUno {

    
    public static void main(String[] args) {
    
        Scanner scanN = new Scanner(System.in);
        Scanner scanS = new Scanner(System.in);
        
        DecimalFormat DecFor = new DecimalFormat("0.00");
        
        String PlayerChoiceBeg;
        String PlayerChoice1;
        String PlayerChoice2;
        String PlayerChoice3;
        String PlayerChoice4;
        String PlayerChoice5;
    
       //Beginning Menu
        System.out.println("\n Type A to start the game");
        System.out.println("\n Type B to exit the program");
        System.out.println("\n Type C for the options menu");
        System.out.println("");
        PlayerChoiceBeg = scanS.nextLine();
        
        if(PlayerChoiceBeg.equalsIgnoreCase("A"))
        {
            System.out.println("\nTime for some sick Expositon.....................");
            System.out.println("Nvm You wake up in a dark room");
            System.out.println("\n Type A to move foward into the abyss");
            System.out.println("\n Type B look around");
            System.out.println("\n Type C to nervously sing \"Country Roads\"");
            System.out.println("");
            PlayerChoice1 = scanN.nextLine();
            
            if (PlayerChoice1.equalsIgnoreCase("A"))
            {    
              System.out.println("\nYou walk forward and find the outline of a obese Skeleton");
              System.out.println("You see a faint outline of a name tag beside it");
              System.out.println("You pick it up it says \"Sans\"");
              System.out.println("\n Type A to Keep the name tag");
              System.out.println("\n Type B to put it back on the Skeleton");
              System.out.println("");
              PlayerChoice2 = scanS.nextLine();
              
              if (PlayerChoice2.equalsIgnoreCase("A"))
              {
               System.out.println();   
              }    
              else if (PlayerChoice2.equalsIgnoreCase("B"))
              {
                  System.out.println("\nYou put the nametag on the Skeleton");
                  System.out.println("A blue flame bursts out of his left eye");
                  System.out.println("Your gonsta have a Bad Time");
              }        
              else
              {
                  System.out.println("\nWrong Command Dummy");
                  System.exit(0);
              }    
                      
            }
            else if (PlayerChoice1.equalsIgnoreCase("B"))
            {
              System.out.println("You find a box of matches beside you");
               System.out.println("\n Type A to light a match");
               System.out.println("\n Type B to keep the box of matches for later");
               System.out.println("");
               PlayerChoice2 = scanS.nextLine();
               
            }
            else if (PlayerChoice1.equalsIgnoreCase("C"))
            {
              System.out.println("\n Almost heaven, West Virginia\n " +
                                 "Blue Ridge Mountains, Shenandoah River\n " +
                                 "Life is old there, older than the trees\n " +
                                 "Younger than the mountains, blowing like a breeze\n " +
                                 "Country roads, take me home\n " +
                                 "To the place I belong\n " +
                                 "West Virginia, mountain mama\n " +
                                 "Take me home, country roads\n " +
                                 "All my memories gather round her\n " +
                                 "Miner's lady, stranger to blue water\n " +
                                 "Dark and dusty, painted on the sky\n " +
                                 "Misty taste of moonshine, teardrop in my eye\n " +
                                 "Country roads, take me home\n " +
                                 "To the place I belong\n " +
                                 "West Virginia, mountain mama\n " +
                                 "Take me home, country roads\n " +
                                 "I hear her voice, in the morning hour she calls me\n " +
                                 "The radio reminds me of my home far away\n " +
                                 "And driving down the road I get a feeling\n " +
                                 "That I should have been home yesterday, yesterday\n " +
                                 "Country roads, take me home\n " +
                                 "To the place I belong\n " +
                                 "West Virginia, mountain mama\n " +
                                 "Take me home, country roads\n " +
                                 "Country roads, take me home\n " +
                                 "To the place I belong\n " +
                                 "West Virginia, mountain mama\n " +
                                 "Take me home, country roads\n " +
                                 "Take me home, down country roads\n " +
                                 "Take me home, down country roads");  
            }
            else 
            {
              System.out.println("Your a dummy");
              System.exit(0);
            }    
        }   
        else if (PlayerChoiceBeg.equalsIgnoreCase("B"))
        {
            System.out.println("Really already fine, be that way Closing Program");
        }
        else if (PlayerChoiceBeg.equalsIgnoreCase("C"))
        {
              System.out.println("\nYou enter the option menu......  A cold breeze passes you by");
              System.out.println("\n Type A for Audio Settings");
              System.out.println("\n Type B for Visual Settings");
              System.out.println("\n Type S For \"Salami\"");
              System.out.println("");
            PlayerChoice1 = scanS.nextLine();
            
            if(PlayerChoice1.equalsIgnoreCase("A"))
            {
               System.out.println("I ain't gonsta make no options you dweeb"); 
            }   
            else if (PlayerChoice1.equalsIgnoreCase("B"))
            {
                System.out.println("\nReally you thought I wouldn't be lazy and actually create options");
            }  
            else if (PlayerChoice1.equalsIgnoreCase("S"))
            {
                System.out.println("\nSometimes you get the \"Salami\", but sometimes the \"Salami\" gets you");
                System.out.println("\n\n\n*The \"Salami\" got you this time bud*");
                System.out.println("\nYou Have Died");
                System.exit(0);
            }
        } 
        
        else
        {
            System.out.println("How did you already fail with the commmands ya dweeb");
        }    
        
        
        
        
        
        
        
        
        
        
    }
    
}
