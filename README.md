# Data types

# Data types are used to store different type of values like characters, Numbers, symbol, etc.

# in JavaScript there are two types of Data Types

( 1 ) Primitive Data type
 
( 2 ) Non Primitive Data type

* Primitive Data type : in JavaScript Primitive Data types are immutable means we can not change or remove some character from a Non-Primitive Data types. these are 
also known as pass by value means when we declare a variable of non-primitive data type then the variable will have the access of only value not the memory location of
the varible that is assigned to that variable.

      Ex: let a = "variable"

      console.log(a)  // variable

      a[2] = 'o'

      console.log(a)  // variable

      Ex:  let a = 10 

      let b = a

      let c = b

      c = 20

      b = 30

      console.log(a,b,c)  // 10 30 20

Types of Primitive Data types : Non primitive Data types are derived from Primitive Data types. in JavaScript non Primitive Data types are mutable, these are also called passed by reference, means the variable has the access of  

( 1 ) String : String is the sequence of zero or more than zero characters bounded with ( '' ) or ( "" ) quotes.

      Ex : 'Rohan', "Rohan", etc.

( 2 ) Number : Number data type represent numbers.

      Ex : 1,2,100,4536, etc.

( 3 ) Undefined : in JavaScript Undefined is a special placeholder that Javascript provides the variables in hoisting phase.

     Ex : console.log(num) // undefined

     var num = 10
     
     console.log(num) // 10
 
( 4 ) Boolean : Boolean accepts only true or false, it is used mostly in if, else conditions.

( 5 ) Null : Null means a variable j=has not been assigned any value its useless, in JavaScript null also represents an empty Object.



* Non Primitive Data type : in JavaSript non primitive data types are derived from primitive data tyes. it is also known as refernce data type.
