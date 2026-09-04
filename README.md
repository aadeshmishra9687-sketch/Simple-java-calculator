import java.util.Scanner;

public class firstclass {
  public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);

    System.out.println("Student Grade Calculator");
    System.out.print("Enter student name: ");
    String studentName = sc.nextLine();
    System.out.print("Enter student ID: ");
    String studentID = sc.nextLine();
    System.out.print("Enter marks1: ");
    double marks1 = sc.nextDouble();
    System.out.print("Enter marks2: ");
    double marks2 = sc.nextDouble();
    System.out.print("Enter marks3: ");
    double marks3 = sc.nextDouble();
    System.out.print("Enter marks4: ");
    double marks4 = sc.nextDouble();
    System.out.print("Enter marks5: ");
    double marks5 = sc.nextDouble();
    double totalmarks = marks1 + marks2 + marks3 + marks4 + marks5;
    double average = totalmarks / 5.0;
    System.out.println("Student Name: " + studentName);
    System.out.println("Student ID: " + studentID);
    System.out.println("Total Marks: " + totalmarks);
    System.out.println("Average Marks: " + average);
    if(average >= 90){
      System.out.println("Grade: A");
    } else if(average >= 80){
      System.out.println("Grade: B");
    } else if(average >= 70){
      System.out.println("Grade: C");
    } else if(average >= 60){
      System.out.println("Grade: D");
    } else {
      System.out.println("Grade: F");
    }
  }
}

