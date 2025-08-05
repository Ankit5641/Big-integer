🧮 BigInt – Arbitrary-Precision Integer Library in C++
A BigInt class implementation in C++ to handle very large integers (arbitrary-precision arithmetic) that are beyond the range of standard data types like int, long, or even long long.

This project supports:

Basic arithmetic (addition, subtraction, multiplication, division, modulo)

Comparison operators

Power (^) and square root (sqrt)

Special functions like Fibonacci, Catalan numbers, and Factorials up to 100

Operator overloading for intuitive usage

🔧 Features
Handles integers of any size using strings and vectors internally

Operator overloading makes usage similar to built-in types

Efficient arithmetic algorithms

No external libraries required – purely standard C++

Additional math features like:

Nth Fibonacci

Nth Catalan number

Factorial of numbers

📂 Project Structure
pgsql
Copy
Edit
BigInt/
│
├── BigInt.cpp         # Contains full class definition and main()
├── README.md          # You're reading it!
🛠️ Requirements
A C++ compiler that supports C++11 or higher

No external libraries needed

🚀 How to Run
Compile the code using g++:

bash
Copy
Edit
g++ BigInt.cpp -o BigInt
Run the program:

bash
Copy
Edit
./BigInt
You will see outputs like comparison checks, arithmetic operations, and computed values for:

First 100 Fibonacci numbers

First 100 Catalan numbers

Factorials from 0 to 100

✅ Sample Output
sql
Copy
Edit
The number of digits in first big integer = 5
first and second are equal!
third is smaller than fourth!
fifth is larger than fourth!
first = 12345
second = 12345
...
Fibonacci 0 = 0
Fibonacci 1 = 1
...
Catalan 5 = 42
Factorial of 5 = 120
...
✍️ Usage Example
cpp
Copy
Edit
BigInt a("999999999999999");
BigInt b("1");
BigInt sum = a + b;
cout << "Sum = " << sum << endl;  // Output: 1000000000000000
📚 Functions Included
BigInt(unsigned long long)

BigInt(string&)

BigInt(const char*)

operator +, -, *, /, %

operator <, <=, >, >=, ==, !=

operator ++, -- (pre and post)

NthFibonacci(int)

NthCatalan(int)

Factorial(int)

sqrt(BigInt&)

Power ^

📌 Note
Overflow and underflow are handled by exception throwing

Inputs are validated; non-digit inputs will throw an error

🤝 Contribution
Pull requests and suggestions are welcome! Let’s make this library even better.

📃 License
This project is open-source and free to use for educational and personal purposes.

🙌 Acknowledgment
This project is inspired by the need to handle large integers in competitive programming and algorithmic challenges.

Developed by Gatea David and customized for real-world usage.
