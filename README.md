# Simple Menu Based Calculator

A C console program (`sc1.c`) that reads two integers and lets the user choose addition, subtraction, multiplication, or division. Division by zero is checked.

## Build and run

```sh
gcc sc1.c -o calculator
./calculator
```

On Windows, run `calculator.exe`.

## Note

When division by zero is selected, the program prints an error and then falls through to the default case, which also prints “Invalid number”. Adding a `break` after the error message prevents this extra output.
