# AdhiraAPP
Database Connection

package PROJECT; 
import java.sql.*; 
public class Connesionprevider { 
    public static Connection getCon(){ 
    
    try { 
        Class.forName("com.mysql.cj.jdbc.Driver"); 
     Connection con; 
        con = 
DriverManager.getConnection("jdbc:mysql://localhost:3306/mydb","root","admin34@"); 
      return con; 
    } 
    catch( Exception e){ 
      return null; 
    } 
   
    } 
  
    }
