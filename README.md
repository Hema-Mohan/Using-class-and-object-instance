# Using-class-and-object-instance

package Car;
import java.util.Scanner;
 class Car{

    String model;
    int year;
    public void inputDetails(){

        Scanner sc = new Scanner(System.in);
        System.out.print("Enter the Car Model: ");
        model = sc.nextLine();
        System.out.print("Enter the  Year of Purchasing: ");
        year = sc.nextInt();
    }
    public void displayDetails(){

        System.out.println("Car Model: " + model);
        System.out.println("Purchased Year: " + year);
    }
}
public class objectandinstance {

    public static void main(String[]args){

        Car mycar = new Car();
        mycar.inputDetails();
        mycar.displayDetails();
    }
    
}

OUTPUT:

Enter the Car Model: Alto 800
Enter the Year of Purchasing: 2022
Car Model: Alto 800
Purchased Year: 2022

