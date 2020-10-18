# Scala Samples

# Hello World
- Example 1
```
object Geeks  { 
    // Main Method  
    def main(args: Array[String])  
    { 
        // prints Hello World 
        println("Hello World!")  
    } 
} 
Geeks.main(Array())
```
- Example 2
```
 object Geeks1 { 
    def main(args: Array[String])  
    { 
        var p = 10
        var q = 30
        var sum = p + q 
        println("The sum of p and q is :"+sum); 
    } 
}  
Geeks1.main(Array())
```
- Example 3
```
class GFG {
    var a: Int = 20
}
object Geeks2 {
    def main(args: Array[String]) {
        var ob = new GFG();
    }
}
Geeks2.main(Array())
```
- Example 4
```

object Geeks3  { 
      
    // Main method 
    def main(args: Array[String]) 
    { 
          
    // Valid Identifiers 
    var `name` = "Siya"; 
    var _age = 20; 
    var Branch = "Computer Science"; 
    println("Name:" +`name`); 
    println("Age:" +_age); 
    println("Branch:" +Branch); 
    } 
}
Geeks3.main(Array())
```
- Example 5
```
object Main  { 
      
    // Main method 
    def main(args: Array[String])  
    { 
          
    // main, _name1, and Tuto_rial are  
    // valid alphanumeric identifiers 
    var _name1: String = "GeeksforGeeks"
    var Tuto_rial: String = "Scala"
      
    println(_name1); 
    println(Tuto_rial); 
    } 
} 
```
- Example 6
```

object Main  { 
      
    // Main method 
    def main(args: Array[String]) 
    { 
          
    // main, x, y, and sum are valid  
    // alphanumeric identifiers 
    var x:Int = 20; 
    var y:Int = 10; 
      
    // Here, + is a operator identifer  
    // which is used to add two values 
    var sum = x + y;  
    println("Display the result of + identifier:"); 
    println(sum); 
    } 
} 
```
- Example 7
```

object Main  { 
      
    // Main method 
    def main(args: Array[String])  
    { 
          
    // num_+ is a valid mixed identifier 
    var num_+ = 20; 
    println("Display the result of mixed identifier:"); 
    println(num_+); 
    } 
} 
```
- Example 8
```
object Test { 
def main(args: Array[String])  
{ 
    var a: Boolean = true
    var a1: Byte = 126
    var a2: Float = 2.45673f 
    var a3: Int = 3
    var a4: Short = 45
    var a5: Double = 2.93846523
    var a6: Char = 'A'
    if (a == true)  
    { 
    println("boolean:geeksforgeeks") 
    } 
    println("byte:" + a1) 
    println("float:" + a2) 
    println("integer:" + a3) 
    println("short:" + a4) 
    println("double:" + a5) 
    println("char:" + a6) 
} 
} 
```
- Example 9
```

object Test { 
      
// Main Method 
def main(args: Array[String]) { 
      
    // taking a variable 
    var a: Int = 50
  
    if (a > 30)  
    { 
  
        // This statement will execute as a > 30 
        println("GeeksforGeeks") 
    } 
} 
} 
```
- Example 10
```

object Test { 
      
// Main Method 
def main(args: Array[String]) { 
      
    // taking a variable 
    var a: Int = 650
  
    if (a > 698)  
    { 
  
        // This statement will not  
        // execute as a > 698 is false 
        println("GeeksforGeeks") 
    } 
      
    else
    { 
          
        // This statement will execute 
        println("Sudo Placement") 
    } 
} 
} 

```
- Example 11
```
// Scala program to illustrate 
// the nested if-else statement 
object Test { 
	
// Main Method 
def main(args: Array[String]) { 
	
	// taking three variables 
	var a: Int = 70
	var b: Int = 40
	var c: Int = 100

	// condition_1 
	if (a > b) 
	{ 
		// condition_2 
		if(a > c) 
		{ 
			println("a is largest"); 
		} 
		
		else
		{ 
			println("c is largest") 
		} 
	
	} 
	
	else
	{ 
		
		// condition_3 
		if(b > c) 
		{ 
			println("b is largest") 
		} 
		
		else
		{ 
			println("c is largest") 
		} 
	} 
} 
} 

```
-Example 12
```

// Scala program to illustrate 
// the if-else-if ladder 
object Test { 
	
// Main Method	 
def main(args: Array[String]) { 
	
	// Taking a variable 
	var value: Int = 50

	if (value == 20) 
	{ 

		// print "value is 20" when 
		// above condition is true 
		println("Value is 20") 
	} 
	
	else if (value == 25) 
	{ 

		// print "value is 25" when 
		// above condition is true 
		println("Value is 25") 
	} 
	
	else if (value == 40) 
	{ 
	
		// print "value is 40" when 
		// above condition is true 
		println("Value is 40") 

	} 
	
	else
	{ 
		
		// print "No Match Found" 
		// when all condition is false 
		println("No Match Found") 
	} 
} 
} 
```
- Example 13
```
// Scala program to illustrate while loop 
object whileLoopDemo 
{ 
	
	// Main method 
	def main(args: Array[String]) 
	{ 
		var x = 1; 

		// Exit when x becomes greater than 4 
		while (x <= 4) 
		{ 
			println("Value of x: " + x); 

			// Increment the value of x for 
			// next iteration 
			x = x + 1; 
		} 
	} 
} 

```
- Example 14
```
// Scala program to illustrate while loop 
object whileLoopDemo { 
	
	// Main method 
	def main(args: Array[String]) 
	{ 
		var x = 1; 

		// Exit when x becomes greater than 4 
		while (x <= 4) 
		{ 
			println("Value of x: " + x); 

			// Increment the value of x for 
			// next iteration 
			x = x + 1; 
		} 
	} 
} 

```
- Example 15
```

object dowhileLoopDemo { 
      
    // Main method 
    def main(args: Array[String]) 
    { 
        var a = 10; 
  
        // using do..while loop 
        do
        { 
            print(a + " "); 
            a = a - 1; 
        }while(a > 0); 
    } 
} 

```
- Example 16
```
// Scala program to illustrate for loop 
object forloopDemo { 
	
// Main Method 
def main(args: Array[String]) { 
		
	var y = 0; 
		
	// for loop execution with range 
	for(y <- 1 to 7) 
	{ 
		println("Value of y is: " + y); 
	} 
} 
} 
```
-Example 17
```
// Scala program to illustrate nested loop 
object nestedLoopDemo { 
	
// Main Method	 
def main(args: Array[String]) { 
	
	var a = 5; 
	var b = 0; 
	
	// outer while loop 
	while (a < 7) 
	{ 
	b = 0; 
		
	// inner while loop 
	while (b < 7 ) 
	{ 
			
		// printing the values of a and b 
		println("Value of a = " +a, " b = "+b); 
		b = b + 1; 
	} 
		
	// new line 
	println() 
		
	// incrementing the value of a 
	a = a + 1; 
		
	// dispalying the updated value of a 
	println("Value of a Become: "+a); 
		
	// new line 
	println() 
	} 

} 
} 
```
- Example 18
```

// Scala program to illustrate the 
// implementation of break 

// Importing break package 
import scala.util.control.Breaks._
object MainObject { 
	
// Main method 
def main(args: Array[String]) 
{ 
	
	// Here, breakable is used to prevent exception 
	breakable 
	{ 
		for (a <- 1 to 10) 
		{ 
			if (a == 6) 
		
				// terminate the loop when 
				// the value of a is equal to 6 
				break 
			else
			println(a); 
		} 
	} 
} 
} 

```
- Example 19
```
// Scala program to illustrate the 
// implementation of break in nested loop 

// Importing break package 
import scala.util.control._

object Test { 
	
// Main method 
def main(args: Array[String]) 
{ 
	var num1 = 0; 
	var num2 = 0; 
	val x = List(5, 10, 15); 
	val y = List(20, 25, 30); 

	val outloop = new Breaks; 
	val inloop = new Breaks; 
	
	// Here, breakable is used to 
	// prevent from exception 
	outloop.breakable 
	{ 
		for (num1 <- x) 
		{ 
		
			// print list x 
			println(" " + num1); 

			inloop.breakable 
			{ 
			for (num2 <- y) 
			{ 
			
			//print list y 
			println(" " + num2); 

			if (num2 == 25) 
			{ 
				
			// inloop is break when 
			// num2 is equal to 25 
			inloop.break; 
			} 
			} 
		
		// Here, inloop breakable 
			} 
		} 
	
	// Here, outloop breakable 
	} 
} 
} 


```
- Example 20
```
// Scala program of integer 
// literals 

// Creating object 
object integer { 

	// Main method 
	def main(args: Array[String]) 
	{ 

		// decimal-form literal 
		val a = 46

		// Hexa-decimal form literal 
		val b = 0xfF

		// Displays results in 
		// integer form 
		println(a) 
		println(b) 
	} 
} 
```
