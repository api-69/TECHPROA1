class Person {
    private String name;
    private int age;

    public void setName(String name) {
        this.name = name;
    }

    public void setAge(int age) {
        if (age >= 0) {
            this.age = age;
        } else {
            this.age = 0;
        }
    }

    public String getName() {
        return name;
    }

    public int getAge() {
        return age;
    }
}

class Student extends Person {
    private String course;

    public void setCourse(String course) {
        this.course = course;
    }

    public String getCourse() {
        return course;
    }

    public void displayInfo() {
        System.out.println("------ Student Information ------");
        System.out.println("Name: " + getName());
        System.out.println("Age: " + getAge());
        System.out.println("Course: " + getCourse());
        System.out.println("---------------------------------");
    }
}

public class SeatworkTwoThirdPartTwo {
    public static void main(String[] args) {
        Student s = new Student();

        s.setName("King");
        s.setAge(16);
        s.setCourse("ICT");
        s.displayInfo();
    }
}