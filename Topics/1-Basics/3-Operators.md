# 3. Operators:
📖**Read:**
<p>
The operators are special symbols that are used to carry out certain operations on the operands.In the Dart there are several built-in Operators.
<br>

♦️ **`Arithmatic operator`** is used to do mathematical operations.<br>
♦️ **`Relational operator`** is used to identify relations between Left & Rigth side.<br>
♦️ **`Logical AND operator`**, returns true when all the conditions are true, otherwise returns false.<br>
♦️ **`Logical OR operator`**, returns false when all the conditions are false, otherwise returns true.<br>
🚩For getting more about operators click [Me](https://www.geeksforgeeks.org/operators-in-dart/)
</p>

## a) Arithmatic Operator:
🎯**Code Example:**
```
void main() {
  int a = 10;
  int b = 20;
  int add = a + b;
  int subst = b - a;
  int multi = a * b;
  double divi = b / a;
  int divi1 = b ~/ a;
  int mod = b  % a;
  print("Addition: $add,\nSubstraction: $subst, \nMultiplication: $multi, \nDivision(fraction type): $divi, \nDivision(integer type): $divi1, \nRemainder: $mod");
}
```

📝**Output:**
> Addition: 30,<br>
  Substraction: 10,<br> 
  Multiplication: 200,<br> 
  Division(fraction type): 2.0,<br> 
  Division(integer type): 2,<br> 
  Remainder: 0

## b) Relational Operator:
🎯**Code Example:**
```
void main() {
  int a = 10;
  int b = 20;
  print("a equals to b: ${a == b}");
  print("a not equals to b: ${a != b}");
  print("a is greater than and equals to b: ${a >= b}");
  print("a is greater than b: ${a > b}");
  print("a is less than and equals to b: ${a <= b}");
  print("a is less than b: ${a < b}");
}
```

📝**Output:**
> a equals to b: false<br>
  a not equals to b: true<br>
  a is greater than and equals to b: false<br>
  a is greater than b: false<br>
  a is less than and equals to b: true<br>
  a is less than b: true

## c) Logical AND Operator:
🎯**Code Example:**
```
void main() {
  int a = 10;
  int b = 20;
  print("Basic Syntax: [Conditions ? expr1 : expr2;] ");
  print("");
  print("a == b && a < b:");
  a == b && a < b ? print("true") : print("false");
  print("");
  print("a != b && a < b:");
  a != b && a < b ? print("true") : print("false");
}
```

📝**Output:**
> Basic Syntax: [Conditions ? expr1 : expr2;]<br>
  a == b && a < b:
  false<br>
  a != b && a < b:
  true

## d) Logical OR Operator:
🎯**Code Example:**
```
void main(){
  int a = 10;
  int b = 20;
  print("Basic Syntax: [Conditions ? expr1 : expr2;] ");
  print("");
  print("a == b || a < b:");
  a == b || a < b ? print("true") : print("false");
  print("");
  print("a == b || a >= b:");
  a == b || a >= b ? print("true") : print("false");
}
```

📝**Output:**
> Basic Syntax: [Conditions ? expr1 : expr2;]<br>
  a == b || a < b:
  true<br>
  a == b || a >= b:
  false
