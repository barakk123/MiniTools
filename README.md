# MiniTools Library

**MiniTools** is a lightweight utility library for C, designed to simplify common tasks quickly and efficiently. The library includes useful functions such as **valid integer input** validation.

The library is available for download and use as `.dll` and `.h` files. You can easily integrate it into your existing projects by including the header file and linking the DLL.

## File Structure

- **minitools.h**: The header file containing the function declarations.
- **minitools.dll**: The dynamic library containing the implemented functions.

## Installation Instructions

1. Download the `minitools.h` and `minitools.dll` files from this repository.
2. Add the `minitools.h` file to your project's directory and include it in your code like this:
   ```
   #include "minitools.h"
   ```
3. Ensure that the `minitools.dll` file is located in your project's environment (e.g., in the same directory as your executable or add the directory path to your platform's library path).

## Usage Example

Here’s a basic example of using the `get_valid_input` function, which prompts the user to enter a valid number and ensures that the input is valid:

```
#include <stdio.h>
#include "minitools.h"

int main() {
    printf("Please enter a valid number:\n");

    int x = get_valid_input(); // Call the function from the library

    printf("You entered: %d\n", x);

    return 0;
}
```

When running the code, the `get_valid_input()` function ensures that the input is a valid integer and that no extra characters are entered.

## Future Plans

This library is in the early stages of development, with plans to expand its functionality with additional utilities and features. As of now, only a basic input validation function is included, but future versions will provide more tools for developers to use in their projects.

We welcome contributions and ideas for new features. Stay tuned for updates!

## How to Contribute

Since this repository only contains the `.dll` and `.h` files, you don't have access to the original C source code (the `.c` file). However, if you have ideas or suggestions for improvements or new functions, feel free to open an **Issue** or a **Pull Request**.

1. **Pull Requests**: You can propose new functions or improvements by **Forking** the repository and submitting a Pull Request. Any contribution will be reviewed by the repository maintainer.
2. **Issues**: If you find any bugs or have feature requests, please feel free to open an **Issue** and describe the problem or feature you'd like to see.

## License

This library is open-source and available for free under the [MIT License](LICENSE.txt) for personal, educational, and open-source projects.

### Commercial Use

If you're planning to use this library in a commercial product or service, or if you require **premium support**, **consultation**, or **custom features**, please contact me for a **Commercial License**.

For small businesses, startups, or individual developers, the library is free to use. However, if the library plays a key role in a highly successful product or service, a commercial license may be requested to ensure continued development and support.

Feel free to reach out if you have any questions regarding commercial use or if you want to discuss custom support options.
