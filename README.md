# Constructors-In-Java
public class New {
    public static void main(String[] args) {
    //Object Instantiation
      MyEmployee Socks = new MyEmployee();
     // Socks.setId(34);
      //Socks.setName("Shiviswag");
        System.out.println(Socks.getId());
        System.out.println(Socks.getName());
    }
}
class MyEmployee{
    private int id;
    private String name;
    // constructor initialisation
   public MyEmployee(){
       id = 45;
       name = "Gaurav";
   } 
   //invoking getters and setters
   // due to private specifier, we used getter setter to set and return value in main class
    public int getId() {
        return id;
    }
    public void setId(int i) {
        this.id=i;
    }
    public String getName() {
        return name;
    }
    public void setName(String n) {
        this.name ="Shiviswag";
    }

   // constructors implementation
    //public MyEmployee(String myName, int myId){
     //id= myId;
     //name= myName;
    }
 //}

