# 1. Variables:
📖**Read:**
<p>
  Variables can be defined by any names excluding some [**_Reserved or Special Words_**]
  <br>
  <b>Examples:</b> print, bool, runtimeType etc.
</p>

# 2. Data-Types:
📖**Read:**
 <p>
   There are mainly 4 kinds of Data-Types in Dart Programming Language including <b> {String, int, double, bool} </b>.
   <br>
   
   ♦️ **`String`** is used to define Texts.<br>
   ♦️ **`int`** is used to define Integer Numbers.<br>
   ♦️ **`double`** is used to define Fraction Numbers.<br>
   ♦️ **`bool`** is used to define True/False.<br>
 </p>
 <br>

🎯**Code Example:**
```
void main(){
  String name = "NAME";
  int id = 12345;
  double height = 6.2;
  bool is_male = true;

  print("name-type: ${name.runtimeType}");
  print("id-type: ${id.runtimeType}");
  print("height-type: ${height.runtimeType}");
  print("is_male-type: ${is_male.runtimeType}");
}
```

📝 **Output:**
> name-type: String<br>
  id-type: int<br>
  height-type: double<br>
  is_male-type: bool

# 3. Operators:
📖**Read:**
<br>
The operators are special symbols that are used to carry out certain operations on the operands.In the Dart there are several built-in Operators.
<br>

♦️ **`Arithmatic`** is used to do mathematical operations.<br>
♦️ **`Relational`** is used to identify relations between Left & Rigth side.<br>
♦️ **`Logical AND`**, returns true when all the conditions are true, otherwise returns false.<br>
♦️ **`Logical OR`**, returns false when all the conditions are false, otherwise returns true.<br>
♦️ **`Unary`**, works on single operands. [++] if for increment & [--] is for decrement.<br>
♦️ **``**
♦️ **``**
♦️ **``**
♦️ **``**
♦️ **``**
♦️ **``**
♦️ **``**
♦️ **``**


 `arithmatic   =>   [+], [-], [*], [/]`<br>
b) `relational   =>   [<=], [<], [>], [>=], [is], [is!]`<br>
c) `logical AND  =>   [&&]`<br>
d) `logical OR   =>   [||]`<br>
e) `unary postfix  =>   [expr++], [expr--]`<br>
f) `unary prefix   =>   [+expr], [-expr], [++expr], [--expr], [!expr]`<br>
g) `assignment    =>   [+=], [-=], [*=], [/=], [&=], [^=]`<br>
h) `bitwise AND, OR, XOR   =>   [&], [|], [^]`<br>
i) `conditional   =>   expr 1 ? [condition1] : [condition2]`<br>
