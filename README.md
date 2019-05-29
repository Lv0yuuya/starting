# starting
Testing programs
import java.io.*;
import java.util.*;

public class NumLineCount{
   public static void main(String[] args) throws FileNotFoundException {
      File a = new File("testfile1.txt");
      Scanner reader = new Scanner(new File("testfile1.txt"));
      int count = 0;
      
      // while loop count file
      while(reader.hasNextLine() ){
         //keep from cash and infinity loop
         String token = reader.nextLine();
         // if statement to skip blank lines and else to count lines
         if(reader.nextLine() == null){
         
         }else{
            count++;
         }
      
      }
      //print total lines with text in them
      System.out.println("Number of lines is = " + count);
   
   }
   

}
