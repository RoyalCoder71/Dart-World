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

📝**Output:**
> name-type: String<br>
  id-type: int<br>
  height-type: double<br>
  is_male-type: bool
