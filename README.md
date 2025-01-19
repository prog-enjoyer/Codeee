import java.util.*;

public class CONVERSION 
{
    public static void main(String args[]) 
    {
        Scanner sc = new Scanner(System.in);
        
        int HOURS, MINS, SECS, totalHours, remainingMinutes, remainingSeconds ; 
        
        System.out.print("Enter number of hours: ");
        HOURS = sc.nextInt(); 
        
        System.out.print("Enter number of minutes: ");
        MINS = sc.nextInt(); 
        
        System.out.print("Enter number of seconds: ");
        SECS = sc.nextInt(); 
        
        
         totalHours = HOURS + (MINS / 60);        
        remainingMinutes = MINS % 60;
        remainingSeconds = SECS % 60; 

       
        System.out.println("Total time is: "  +totalHours+ " hours and " +remainingMinutes+ " minutes.");
    }
}
