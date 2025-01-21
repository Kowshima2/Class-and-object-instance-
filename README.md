# Class-and-object-instance-
class Person {
   
    String name;
    int age;
    Person(String name, int age) {
        this.name = name;
        this.age = age;
    }
    void displayDetails() {
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
    }
}
public class Main {
    public static void main(String[] args) {
        Person person1 = new Person("Alice", 25); 
        Person person2 = new Person("Bob", 30);   
        System.out.println("Person 1 Details:");
        person1.displayDetails();

        System.out.println("\nPerson 2 Details:");
        person2.displayDetails();
    }
}

Output 

Person 1 Details:
Name: Alice
Age: 25

Person 2 Details:
Name: Bob
Age: 30
