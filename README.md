# Java-Exp-10
# Inheritance
# Aim:
To write a Java program to Create a class named 'Member' having certain members.

# Algorithm
Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class called "Employee" and create required statements.

Step 3 : Create a another class called "Manager" and create required statements.

Step 3 : Create another class,called the "Member" and create required statements

Step 4 : Create a main class,called the "Solution".

Step 5 : Using the 'extends' keyword you can inherit classes, do the same with above created class.

Step 6 : Display the statements from the first and secomd Class using Solution Class in the terminal.

# Program
public class Employee extends Member {<br>
    public String specialization;<br>
}<br>
public class Manager extends Member {<br>
    public String departemnt;<br>
}<br>
public class Member {<br>
    public String name;<br>
    public int age;<br>
    public String ph;<br>
    public String address;<br>
    public String sal;<br>
    public void dissal() {<br>
        System.out.println("The Salary of this employee is: " + sal);<br>
    }<br>
}<br>
public class Type {<br>
    public static void main(String[] args) {<br>
        Total emp1 = new Total();<br>
       Proanddiff emp2 = new Proanddiff();<br>
        emp1.name = "Sham";<br>
        emp1.age = 20;<br>
        emp1.ph = "8610750378";<br>
        emp1.address = "Salem";<br>
        emp1.sal = "900k";<br>
        emp2.departemnt = "AI-DS";<br>
        emp1.specialization = "Data Analyst";<br>
        System.out.println(emp1.name + "\n" + emp1.age + "\n" + emp1.ph + "\n" + emp1.address<br>
                           + "\n" + emp1.specialization + "\n" + emp2.departemnt);<br>
        emp1.dissal();<br>

   }<br>
}<br>
# Output:
![image](https://github.com/Anuayshh/Java-Exp-10/assets/127651217/224e901e-44b3-472a-af95-9efaec787be5)


# Result
We have successfully created a Java program using inheritance one class can acquire the properties of others.
