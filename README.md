# Assignment-Day-1
Online Classes - Assignments

Question 1: What is a variable in C/C++?
Answer: A variable is a named memory location used to store data that can be changed during
program execution.


Question 2: Why do we use variables in programs?
Answer: Variables are used to store and manipulate data during program execution.


Question 3: What is the difference between a variable name and its value?
Answer: A variable name identifies the storage location, while the value is the data stored in it.


Question 4: Which of the following is a valid variable name? a) 2num b) total_marks c) for d) my
marks
Answer: b) total_marks


Question 5: Why is Age different from age?
Answer: C++ is case-sensitive, so Age and age are different variables.


Question 6: Can a variable name contain spaces? Why?
Answer: No. Variable names cannot contain spaces.


Question 7: Can a variable name start with an underscore (_) ?
Answer: Yes.


Question 8: What happens if two variables have the same name in the same scope?
Answer: A compilation error occurs.


Question 9: Write three meaningful variable names for storing student information.
Answer: studentName, studentAge, studentMarks.


Question 10: Which naming convention is better and why: studentMarks or sm?
Answer: studentMarks because it is more descriptive.


Question 11: What is a data type?
Answer: A data type defines the type of value a variable can store.


Question 12: Which data type is used to store whole numbers?
Answer: int


Question 13: Which data type is used to store decimal values?
Answer: float or double


Question 14: What is the difference between float and double?
Answer: double provides greater precision.


Question 15: Which data type stores a single character?
Answer: char


Question 16: Which data type stores True/False values?
Answer: bool


Question 17: What data type is suitable for storing a person's name? 
Answer: string


Question 18: Predict the output: int age=18; cout<<age;
Answer: Output: 18


Question 19: Identify the data type: 25, 3.14, 'A', true.
Answer: int, double/float, char, bool


Question 20: What happens if you store a decimal number in an int variable?
Answer: The decimal part is removed.


Question 21: What is the purpose of cin?
Answer: To take input from the user.


Question 22: What is the purpose of cout?
Answer: To display output.


Question 23: Which symbol is used with cin?
Answer: >>


Question 24: Which symbol is used with cout?
Answer: <<


Question 25: Explain: cin >> age;
Answer: Reads a value into age.


Question 26: Explain: cout << age;
Answer: Displays the value of age.


Question 27: What is the purpose of endl?
Answer: Moves to the next line.


Question 28: Write a statement to input a student's marks.
Answer: cin >> marks;


Question 29: Write a statement to display 'Welcome to C++'.
Answer: cout << "Welcome to C++";


Question 30: Predict the output: cout << 'Programming';
Answer: Invalid usage because single quotes are for a single character.


Question 31: What is an operator?
Answer: A symbol that performs an operation.


Question 32: Which operator is used for addition?
Answer: +


Question 33: What is the result of 10 % 3?
Answer: 1


Question 34: What is the result of 8 % 2?
Answer: 0


Question 35: Which operator checks equality?
Answer: ==


Question 36: What is the difference between = and == ?
Answer: = assigns, == compares.


Question 37: What is the result of 5 > 3?
Answer: true


Question 38: What does && represent?
Answer: Logical AND


Question 39: What does || represent?
Answer: Logical OR


Question 40: What does ! represent?
Answer: Logical NOT


Question 41: Write a program to print Hello World.
Answer: #include <iostream>
using namespace std;
int main(){
cout << "Hello World";
return 0;
}


Question 42: Write a program to input two numbers and display their sum.
Answer: #include <iostream>
using namespace std;
int main(){
int a,b;
cin>>a>>b;
cout<<a+b;
return 0;
}


Question 43: Write a program to calculate the area of a rectangle.
Answer: #include <iostream>
using namespace std;
int main(){
double l,w;
cin>>l>>w;
cout<<l*w;
return 0;
}


Question 44: What formula is used to calculate Simple Interest?
Answer: SI = (P × R × T) / 100


Question 45: Write a program to calculate Simple Interest.
Answer: #include <iostream>
using namespace std;
int main(){
double P,R,T;
cin>>P>>R>>T;
cout<<(P*R*T)/100;
return 0;
}


Question 46: Why is a temporary variable used while swapping two numbers?
Answer: To avoid losing data during swapping.


Question 47: Swap the values: a=10, b=20.
Answer: After swapping: a=20, b=10


Question 48: What formula is used to convert Celsius into Fahrenheit?
Answer: F = (C × 9/5) + 32 


Question 49: What is the Fahrenheit value of 0°C?
Answer: 32°F


Question 50: Why can integer division give incorrect results in the Celsius-to-Fahrenheit program?
Answer: It removes decimal precision.