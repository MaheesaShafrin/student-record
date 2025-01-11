# student-record
class StudentRecord {
private String name;
private int age;
public StudentRecord(String name, int age) {
this.name = name;

this.age = age;
}
public void displayRecord() {
System.out.println(&quot;Name: &quot; + name);
System.out.println(&quot;Age: &quot; + age);
}
}
public class StudentRecordExample {
public static void main(String[] args) {
StudentRecord student = new StudentRecord(&quot;Emma&quot;, 20);
student.displayRecord();
}
}
Output
Name: Emma
Age: 20
