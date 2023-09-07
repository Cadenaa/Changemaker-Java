Changemaker-Java
Simple Java Change Maker Program
import java.util.Scanner;
public class ChangeMakingProgramExample {

    public static void main(String[] args) {
        System.out.println(" Enter a whole numer from 1 to 99.");
        System.out.println(" I will find a combination of coins.");
        System.out.println(" that equals the amount of change");
        Scanner keyboard = new Scanner(System.in);
        int amount = keyboard.nextInt();
        int originalAmount = amount;
        int quarters = amount /25; //maxium number of quarters in amount 
        amount = amount%25; // changer left ocer after giving out quarters
        int dimes = amount / 10; 
        amount = amount%10;
        int nickels = amount / 5;
       amount = amount%5;
       int pennies = amount;
       System.out.println(originalAmount + " cents in couns can be given as:");
       System.out.println(quarters + " quarters");
       System.out.println(dimes + " dimes");
       System.out.println(nickels + " nickels and");
       System.out.println(pennies + " pennies"); //Very Simple Program to reveiw back on fundementals of Java 
