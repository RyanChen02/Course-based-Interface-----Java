TextAnalyzer: 

package Ultimate;

import java.awt.Font;
import java.awt.Graphics;
import java.awt.Graphics2D;
import java.awt.RenderingHints;
import java.awt.image.BufferedImage;
import java.util.Scanner;

public class TextAnalyzer {
	

public void saying () {
	System.out.println("My favorite saying at John 3:16 : For God so loved the world, that he gave his only begotten Son, that whosoever believeth in him should not perish, but have everlasting life --- (King James Bible Version ).");
}


public void encouragement() {
	System.out.println("Encourage word for you is ---- Psalm 46:1 God is our refuge and strength, a very present help in trouble. ");
}

public void textart() {

    int width = 100;
    int height = 30;

    BufferedImage image = new BufferedImage(width, height, BufferedImage.TYPE_INT_RGB);
    Graphics g = image.getGraphics();
    g.setFont(new Font("SansSerif", Font.BOLD, 24));

    Graphics2D graphics = (Graphics2D) g;
    graphics.setRenderingHint(RenderingHints.KEY_TEXT_ANTIALIASING,
            RenderingHints.VALUE_TEXT_ANTIALIAS_ON);
    graphics.drawString("JAVA", 10, 20);

   
    for (int y = 0; y < height; y++) {
        StringBuilder sb = new StringBuilder();
        for (int x = 0; x < width; x++) {
        	sb.append(image.getRGB(x, y) == -16777216 ? " " : "$");}

        if (sb.toString().trim().isEmpty()) {
            continue;}
        System.out.println(sb);}
}

public void open() {
	System.out.println("Welcome!");
}

public void stringprocessor() {
	  Scanner input=new Scanner(System.in);
	    int i=0;
		char c; 
		char r;
		int f;
		String answer; 
		System.out.println("Do you want to create a new string?");
		answer=input.nextLine();
	    while ((answer.charAt(0)=='y')&(i<=5)) 
	    {i++; 
	    	 System.out.println("Input the String:");
	    	 String str=input.nextLine();
			 System.out.println("Input the character you want to replace:");
			  c = input.next().charAt(0);
			 System.out.println("Input the character you want to be replaced with");
			  r = input.next().charAt(0);
			 System.out.println(c + " " + r);
		     str = str.replace(c,r);
		     System.out.println(str);
		   
			 System.out.println("Insert the location you want to insert:");
			 f =input.nextInt();
			 System.out.println("Insert the character you want to insert:");
			 r = input.next().charAt(0);
			 input.nextLine();
			 str=(str.substring(0,f)+r+str.substring(f,str.length()));
			 System.out.println(str);
			 
			 answer=input.nextLine();
			 System.out.println("Do you want to create a new string?");
			 answer=input.nextLine();
	    }
	}
}

