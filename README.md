# hello-world
Learning Java, what do I need to improve

package learningjava;
import java.util.Scanner;
public class Information 
{
 public static void main(String[] args)
 {  
     Scanner in = new Scanner(System.in);
     String name;
     String address;
     String city;
     
     System.out.println("Enter your first and last name");
     name = in.nextLine();
     
     System.out.println("Enter your Address");
     address = in.nextLine();
     
     System.out.println("Enter your city");
     city = in.nextLine();
     
     System.out.println("Here is the information you provided: ");
     System.out.println(name);
     System.out.println(address);
     System.out.println(city);
     
     if(!name.equals("address, city")) 
     
         System.out.println("Congratulations you pass");
      
     else 
     
        System.out.println("The Information you Entered is incorrect. "); 
       
 }
}
