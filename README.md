class Student{
    String name;
    int rollNumber;
    char grade;
    public Student(String name,int rollNumber,char grade){
        this.name = name;
        this.rollNumber = rollNumber;
        this.grade = grade;
    }
    public void displayDetails(){
        System.out.println("Name:\t"+name);
        System.out.println("Rollnumber:\t"+rollNumber);
        System.out.println("grade:\t"+grade);
    }
}
public class Main {
    public static void main(String[] args) {
    Student student1=new Student("Diya",33,'A');
        student1.displayDetails();
    }
}