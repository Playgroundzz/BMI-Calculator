# BMI-Calculator
...trying out this Github thing by coding a BMI-Calculator

import java.util.Scanner;

public class BMI {
public static void main(String[] args) {
  
  double weight, height, bmi;
  Scanner sc = new Scanner(System.in);
  
  System.out.println("Type in your Bodyweight in kilograms: ");
  weight = sc.nextDouble();
  
  System.out.println("Type in your Height in metres: ");
  height = sc.nextDouble();
  
  bmi = weight / (height * height);
  System.out.println("Your BMI is at: " + bmi);
  }
}
//next step: add loops... 
