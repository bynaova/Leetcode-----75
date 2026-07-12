Eina ngasi khngjaba da 
StringBuilder hyba ma sijin nei maci na class amani , chumnagi String dagi khetnaba ma lei maci su class ni
StringBuilder d semdok semjin hptok hpchin twba yahalli ,
String d yade amuktng semkhrbadi.
public class Demo {
    public static void main(String[] args) {
        StringBuilder sb = new StringBuilder("Hello");
        
        sb.append(" World");        // Hello World
        sb.insert(5, ",");          // Hello, World
        sb.replace(0, 5, "Hi");     // Hi, World
        sb.delete(3, 4);            // Hi World
        sb.reverse();               // dlroW iH
        
        System.out.println(sb.toString());
    }
}
c khei twba yaiko OK ngasigi 

