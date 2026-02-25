import java.util.ArrayList;

class Student {
    private int id;
    private String name;

    Student(int id, String name) {
        this.id = id;
        this.name = name;
        System.out.println("Student created: " + name);
    }

    void displayInfo() {
        System.out.println("ID: " + id + ", Name: " + name);
    }

    @Override
    protected void finalize() throws Throwable {
        System.out.println("Garbage collecter destroying student object: " + name);
    }
}

public class SeatworkNineThird {
    public static void main(String[] args) {
        System.out.println("=== Student Record System ===");

        ArrayList<Student> students = new ArrayList<>();

        students.add(new Student(1, "Juan"));
        students.add(new Student(2, "Maria"));
        students.add(new Student(3, "Pedro"));

        System.out.println("\n--- Displaying Student Records ---");
        for (Student student : students) {
            student.displayInfo();
        }

        System.out.println("\n--- Removing Student Records ---");
        students.remove(0);
        students.remove(0);

        System.out.println("\nRequesting Garbage Collection...");
        System.gc();

        System.out.println("\n--- Creating Temporary Student Objects ---");
        for (int i = 4; i <= 20; i++) {
            Student temp = new Student(i, "Temp Student" + i);
        }

        System.out.println("\n--- Clearing Remaining References ---");
        students = null;

        System.out.println("\nRequesting Garbage Collection Again...");
        System.gc();

        try {
            Thread.sleep(2000);
        } catch (InterruptedException e) {
            System.out.println(e);
        }

        System.out.println("\n=== End of Student Record System ===");
    }
}