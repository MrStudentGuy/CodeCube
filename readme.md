# CodeCube: Learn Programming Through Play

**Project Description**

CodeCube is an innovative educational tool designed to make programming fun and accessible for kids and beginners. It's a Unity-based platform that combines the excitement of gaming with the fundamentals of coding. With CodeCube, you can learn programming concepts by controlling a virtual vehicle using a simple and intuitive programming language. <br> 
CodeCube was created to introduce kid's to text-based programming, instead of starting off with block-based programming. This allows the transition to mainstream production languages such as C++/C, C#, or Java easier.


## Getting Started

### Installation

To get started with CodeCube, follow these steps:

1. Clone the CodeCube repository from [GitHub](https://github.com/MrStudentGuy/CodeCube).
2. Open the project in Unity.
3. Explore the code and assets to understand how the game is built.
4. Run the game to start coding and playing!

### Basic Syntax

CodeCube uses a unique and user-friendly syntax to teach programming concepts. Here's an overview of the basic syntax:

- **Commands**: The language operates on verbs followed by parameters, terminated by a semicolon (`;`). Each line is executed with a 0.3-second interval.

- **Execution Order**: Code is executed from top to bottom, ensuring that no asynchronous actions can take place.

- **Code Comments**: Lines starting with two forward slashes ('//') are ignored by the parser, allowing for code comments.

#### Example

```code
MOVE(5);
// This command will move the vehicle by 5 units.
```

### Available Commands

1. **MOVE(X)**: Moves the vehicle by X units.

   Example:
   ```code
   MOVE(5);
   // This command will move the vehicle by 5 units.
   ```

2. **ROTATE(X)**: Rotates the vehicle by X degrees.

   Example:
   ```code
   ROTATE(90);
   // This command will rotate the vehicle by 90 degrees.
   ```

3. **REPEAT(X)**: Repeats all the commands inside the curly brackets X times.

   Example:
   ```code
   REPEAT(4)
   {
       MOVE(1);
       ROTATE(90);
   }
   // This code repeats the MOVE(1) and ROTATE(90) commands 4 times.
   ```

4. **STOP()**: Stops execution and parsing of code.

5. **RESET()**: Sets `transform.position` of the vehicle to the point where play mode began.

## License

CodeCube is released under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html), which means it's free to use, modify, and distribute for educational purposes in compliance with the terms of this license.

Please review the full text of the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html) for a detailed understanding of your rights and responsibilities when using, modifying, or distributing CodeCube.

## Contributing

CodeCube is an open-source project designed for educational purposes. We welcome contributions from the community to improve and expand the platform. If you have ideas for new features, enhancements, or bug fixes, please feel free to submit pull requests or open issues on our [GitHub repository](https://github.com/MrStudentGuy/CodeCube).

## Contact

For questions, feedback, or support, please contact us at [ftcmatrix2021@gmail.com](mailto:ftcmatrix2021@gmail.com).

Start your programming journey with CodeCube and discover the joy of learning through play! Happy coding!
