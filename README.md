# Email-Application
Java code for Email Application
package mail;
import java.util.Scanner;

import java.util.Calendar;

public class Password{

	    public static void main(String[] args) {
	    	
	    	 Scanner sc =new Scanner (System.in);
	    	 int n=4;
	    	 for(int i=0;i<n;i++) {
		      System.out.print("Enter function( login, compose, change password,exit ): ");
		      String ch =sc.nextLine();
		      if(ch.equals("login"))
	   	      {
	             System.out.print("Enter email id: ");
	             String id = sc.nextLine();
	             System.out.print("Enter password: ");
	             String password = sc.nextLine();

	             if (id.equals(id) && password.equals(password)) {
	                 System.out.println(" User successfully logged-in.. ");
	             } else {
	                 System.out.println(" In valid emailid or password ");
	             }
	 	        	      }
	else
	    if(ch.equals("compose"))
	    {
	    Calendar c=Calendar.getInstance();
	    System.out.print("Enter email id: ");
	    String mail=sc.nextLine();
	    System.out.print("Password: ");
	    String Password=sc.nextLine();
	          if(Password.equals(Password))
	    {
	    System.out.println("Logged On!");
	    System.out.print("To:   ");
	    String User=sc.nextLine();
	    System.out.print("From:   ");
	    String From=sc.nextLine();
	    System.out.println("");
	    System.out.println("Letter Content:");
	    String Body=sc.nextLine();
	    System.out.println("");
	    System.out.println("Time:"+c.get(Calendar.HOUR)+":"+c.get(Calendar.MINUTE)+" PM");
	    System.out.println("From "+From+",");
	    System.out.println(Body);
	    System.out.println("");
	    System.out.println("Mail sent!");
	      }
	    }
	    else
	    	if(ch.equals("change password"))  {  
	    		int n1=2;
	     		for(int a=0;a<n1;a++){
	     			System.out.println("Enter the old password:");
	    			  String Password=sc.nextLine(); 
	    			    if(Password.equals(Password)) {
	    			    	System.out.println("Enter the new password:");
	    	    			  String newPass=sc.nextLine(); 
	    	    				System.out.println("Re-enter the password:");
	    	      			  String conNewPass=sc.nextLine(); 
	    			        if (newPass.equals(conNewPass)) {
	    			            Password = newPass;
	    			            System.out.println("changed password ");
	    			            break;
	    			         
	    			        } else {
	    			        	
	    			        	System.out.println("Try again ");
	    			        	continue;
	    			        	}
	    			    }
	     		}
	    	}
	    			        		
	    	 else
		    	 if(ch.equals("exit"))  
		    	 {
		    		 break;
		    		 }
		      }
	    	 }
}


		    	  

	    	  
	    	  
  	 
	   	   
	    	  [Java code of Email Application.txt](https://github.com/pradeepa4899/Email-Application/files/8380832/Java.code.of.Email.Application.txt)
