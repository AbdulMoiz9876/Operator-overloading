# Operator-overloading
In C++, we can make operators work for user-defined classes. 
This means C++ has the ability to provide the operators with a special meaning for a data type, this ability is known as operator overloading.
Operator overloading can be of different operator types like uniryoperator,binaryoperators,etc.
Important points about operator overloading 
1) For operator overloading to work, at least one of the operands must be a user-defined class object.
2) Assignment Operator: Compiler automatically creates a default assignment operator with every class. The default assignment operator does assign all members of the right side to the left side and works fine in most cases (this behaviour is the same as the copy constructor). See this for more details. 
3) Conversion Operator: We can also write conversion operators that can be used to convert one type to another type. 
 
