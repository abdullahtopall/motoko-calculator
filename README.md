# Motoko Calculator

This project is a simple calculator implemented using the Motoko programming language. The calculator performs basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

- Addition (`+`)
- Subtraction (`-`)
- Multiplication (`*`)
- Division (`/`)

## Getting Started

### Prerequisites

To work with this project, you need to have the following:

- **Motoko Playground**: You can run this project directly on the [Motoko Playground](https://m7sm4-2iaaa-aaaab-qabra-cai.raw.ic0.app/) online environment, where you can write and execute Motoko code.

### Running the Project

1. Open [Motoko Playground](https://m7sm4-2iaaa-aaaab-qabra-cai.raw.ic0.app/).
2. Copy the code from the project files into the Motoko Playground editor.
3. Compile and run the project.

### Example Usage

```motoko
actor {
  public func add(x: Int, y: Int): Int {
    return x + y;
  }

  public func subtract(x: Int, y: Int): Int {
    return x - y;
  }

  public func multiply(x: Int, y: Int): Int {
    return x * y;
  }

  public func divide(x: Int, y: Int): ?Int {
    if (y == 0) {
      return null;
    } else {
      return ?(x / y);
    }
  }
}
