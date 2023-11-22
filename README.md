### Types of Numbers

Integers are whole numbers, positive or negative. For instance, `3` and `-2` are examples of integers.

Floating-point numbers have decimal points or use exponential notation (`e` or `E`). For example, `3.0`, `-2.1`, and `4E2` are floating-point numbers.

#### Integer Types
```cpp
int number = 10;
long big_number = 1234567890;
short small_number = 5;
```
#### Floating-Point Types
```cpp
float pi = 3.14;
double precise_pi = 3.14159265359;
```
#### Character Types
```cpp
char letter = 'A';
```
#### Boolean Type
```cpp
bool is_valid = true;
```
#### Other Types
```cpp
string greeting = "Hello, World!";
int arr[5] = {1, 2, 3, 4, 5};

int x = 10;
float y = 4.5;
char z = 'Z';
bool is_active = false;

int a = 10;
double b = 4.5;
int c = a + b; // c will be 14.5, but truncated to 14 (losing the decimal part)

double result = double(a) + b; // result will be 14.5 (a is temporarily cast to double)

const int MAX_VALUE = 100;
const float PI = 3.14159;

int num1 = 10;
int num2 = 5;

int sum = num1 + num2; // sum will be 15
bool isEqual = (num1 == num2); // isEqual will be false
```

Functions are blocks of code that perform specific tasks. They can take parameters (inputs) and return values.

### Basic Arithmetic

```cpp
// Addition
2 + 1  
```
> 3

```cpp
// Subtraction
2 - 1 
```
> 1

```cpp
// Multiplication
2 * 2  
```
> 4

```cpp
// Division
3 / 2  
```
> 1.5

```cpp
// Floor Division
int result = 7 / 4;

```
> 1

```cpp
// Modulo
7 % 4  
```
> 3

```cpp
// Powers
pow(2, 3)  
```
> 8

```cpp
// Roots
sqrt(4)  
```
> 2.0

```cpp
// Order of Operations
2 + 10 * 10 + 3  
```
> 105

```cpp
(2 + 10) * (10 + 3)  
```
> 156
