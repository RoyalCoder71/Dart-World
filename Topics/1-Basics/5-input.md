# 5. Input
📖**Read:**
<p>
  In Dart programming language, you can take standard input from the user through the console via the use of <b>.readLineSync()</b> function.
  To take input from the console you need to import a library, named <b>dart:io</b> from libraries of Dart.
</p>

## a. Input(String type):
🎯**Code Example:**
```
// importing dart:io file
import 'dart:io';
 
void main()
{
    print("Enter your name?");
    // Reading name of the user
    String name = stdin.readLineSync()!; // null safety in name string
 
    // Printing the name
    print("Hello, dear $name! Welcome to my Github");
}

```
