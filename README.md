# Java Explorer

This repository contains a simple Java program that prints "Hello World" to the console. It demonstrates a basic setup for running Java code locally using Java SE 17.

## Project Structure

```
java-explorer
├── HelloWorld.java  # Java source file
└── HelloWorld.class # Compiled Java bytecode file
```

## Getting Started

### Prerequisites

- **Java SE 17**: Make sure Java SE 17 is installed on your system. You can check your version by running:
  ```sh
  java -version
  ```

### Running the Program

1. **Compile the Java file**: In PowerShell or your preferred command line, navigate to the directory containing `HelloWorld.java`, then run:
   ```sh
   javac HelloWorld.java
   ```
   This will generate a `HelloWorld.class` file.

2. **Run the compiled program**: Execute the program with:
   ```sh
   java HelloWorld
   ```
   You should see the following output:
   ```
   Hello World
   ```

### Example

PowerShell 7.4.6:
```sh
PS C:\Home\DEV\Java-SE-17\java-explorer> javac HelloWorld.java
PS C:\Home\DEV\Java-SE-17\java-explorer> java HelloWorld
Hello World
PS C:\Home\DEV\Java-SE-17\java-explorer>
```

## Code

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```

## License

This project is licensed under the MIT License.