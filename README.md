### Here are some examples of basic Dart programming concepts, including printing, variables, loops, and taking input.

# 1. Print Statements
   ```dart
    void main() {
      print('Hello, World!');
      print('Welcome to Dart programming.');
    }
   ```

# 2. Variables
   ```dart
     void main() {
      // Declaring variables
      int age = 25;
      double height = 5.9;
      String name = 'Alice';
      bool isStudent = true;
    
      // Printing variables
      print('Name: $name');
      print('Age: $age');
      print('Height: $height');
      print('Is Student: $isStudent');
    }
   ```

# 3. Loops
   
   - For loop:
       ```dart
          void main() {
          for (int i = 0; i < 5; i++) {
            print('For Loop Iteration: $i');
          }
        }
       ```
       
   - While loop:
       ```dart
          void main() {
          int i = 0;
          while (i < 5) {
            print('While Loop Iteration: $i');
            i++;
          }
        }
       ```


# 4. Input From User
   
   To take input from the user, you can use the dart:io library.
   ```dart
      import 'dart:io';
      
       void main() {
           stdout.write('Enter your name: ');
           String? name = stdin.readLineSync();  // Reading input as a string
         
           stdout.write('Enter your age: ');
           String? ageInput = stdin.readLineSync();  // Reading input as a string
           int age = int.parse(ageInput!);  // Converting the string input to an integer
         
           print('Hello, $name! You are $age years old.');
    }
   ```

# 5. Conditional Statements

    ```dart
          void main() {
            int age = 20;
          
            if (age >= 18) {
              print('You are an adult.');
            } else {
              print('You are a minor.');
            }
          }
    ```

# 6. Functions

    ```dart
        void main() {
          printHello();
          int sum = add(5, 3);
          print('Sum: $sum');
        }
        
        void printHello() {
          print('Hello from a function!');
        }
        
        int add(int a, int b) {
          return a + b;
        }
    ```

# 7. Lists (Arrays)
   
   ```dart
         void main() {
        List<int> numbers = [1, 2, 3, 4, 5];
      
        for (int number in numbers) {
          print('Number: $number');
        }
      }
   ```

# 8. Maps (Dictionaries)

   ```dart
         void main() {
        Map<String, String> capitals = {
          'USA': 'Washington, D.C.',
          'India': 'New Delhi',
          'Japan': 'Tokyo'
        };
      
        capitals.forEach((country, capital) {
          print('The capital of $country is $capital.');
        });
      }
   ```
   
# 9.  Classes and Objects

    ```dart
          void main() {
          Person person = Person('John', 30);
          person.greet();
        }
      
        class Person {
          String name;
          int age;
        
          Person(this.name, this.age);
        
          void greet() {
            print('Hello, my name is $name and I am $age years old.');
          }
        }
    ```


These examples cover basic concepts in Dart programming. You can run these snippets to see how each concept works. 

