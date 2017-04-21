# GoonDefense
Advance Comp Sci tower defense game

import java.io.*;
import java.awt.*;
import javax.swing.*;
import java.util.*;
import java.io.IOException;

public class GoonDefenseDriver
{
   public static JFrame frame;
   
   public static void main(String args[])throws IOException
   {
      frame = new JFrame("Goon Defense");
      frame.setSize(1000,700);
      frame.setVisible(true);
   }
   
}






import java.io.*;
import java.awt.*;
import javax.swing.*;
import java.util.*;
import java.awt.event.*;

public class Screen extends JPanel implements MouseListener, MouseMotionListener
{
   public Screen()
   {
   
   }
   
   public void paintComponent(Graphics g)
   {
   
   }
}
