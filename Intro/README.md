# Some interesting features to Java

- char is 2 bytes -> Unicode (USHRT_MAX)
- sugar sintax - int number = 1_000_000, int loc = 0xCAFE_BABE
- using unitialized variable - Compile Error!, Javac doesn't add magically default value
- Wrapper classes - they have specific functions for their primitive type
- String pool - There is a difference between String str = "Hi"//referenced str and ... str = new String("Hi")//Heap, independent obj
