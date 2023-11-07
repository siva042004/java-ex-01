# EX-5-Create-a-table-by-the-following
```
class Employee {
    String name;
    int yearOfJoining;
    String address;

    public Employee(String name, int yearOfJoining, String address) {
        this.name = name;
        this.yearOfJoining = yearOfJoining;
        this.address = address;
    }
}

public class EmployeeInformation {
    public static void main(String[] args) {

        Employee employee1 = new Employee("Robert", 1994, "64C- WallsStreet");
        Employee employee2 = new Employee("Sam", 2000, "68D- WallsStreet");
        Employee employee3 = new Employee("John", 1999, "26B- WallsStreet");

        // Print the table header
        System.out.printf("%-15s %-20s %-20s%n", "Name", "Year of Joining", "Address");

        // Print information for each employee
        printEmployeeInformation(employee1);
        printEmployeeInformation(employee2);
        printEmployeeInformation(employee3);
    }

    // Function to print employee information in a formatted manner
    private static void printEmployeeInformation(Employee employee) {
        System.out.printf("%-15s %-20d %-20s%n", employee.name, employee.yearOfJoining, employee.address);
    }
}

```
# Output
![Screenshot (69)](https://github.com/21002624/EX-5-Create-a-table-by-the-following/assets/113762183/8e2c0a9e-555f-4fcc-92ef-a0a59c44f2df)

