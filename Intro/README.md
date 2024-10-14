# Some interesting features to Java

- char is 2 bytes -> ***Unicode*** (USHRT_MAX)
- ***Sugar syntax*** -> int number = 1_000_000, int loc = 0xCAFE_BABE
- Using unitialized variable -> Compile Error!, ***Javac*** doesn't add magically default value
- ***Wrapper classes*** -> They have specific functions for their primitive type
- ***String pool*** -> There is a difference between String str = "Hi"//*referenced* str and ... str = new String("Hi")//*Heap, independent object*
