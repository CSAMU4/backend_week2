# backend_week2
_week two notes - conditions and loops_

# java - boolean operations 

the computer needs to make decisions to complete a task; and by making decisions the data needs to be compared and evaluated to proceed. boolean values make it possible to make decisions via yes or no manner. in java, that yes or no is represented by true or false 'if statements'.  

  firstly, at least two variables need to be **compared**

_**boolean expression - legally old enough to drive example in java**_

    int ageRequiredToDrive = 16;
  
    int currentAge = 14;
  
    boolean canPersonDrive = (currentAge >= ageRequiredToDrive); 
  
    System.out.println(canPersonDrive);

**list of boolean operations** 
 
 less than: < 
 
 greater than: >
 
 less than or equal to: <=
 
 greater than or equal to: >=
 
 equal: ==
 
 secondly, the variables need to be **evaluated** through conditionals or if statements that are yes or no OR true or false 
 
    written in java as: 
    
     if (/*Boolean expression*/) {
     
     }
 
 
 _**boolean expression - legally old enough to drive example in java**_ if statement 
 
    if (/canPersonDrive*/) {
    
      System.out.println("This person can drive!");
      
      }
