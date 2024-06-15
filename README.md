# ETH+AVAX-Assessment

# ErrorHandlingContract

This project demonstrates a Solidity smart contract that uses `require()`, `assert()`, and `revert()` statements to handle errors and enforce conditions. The contract includes functions to set a value and perform division with appropriate error handling.

## Purpose

The purpose of this project is to provide an example of how to use error handling statements in Solidity smart contracts. This helps developers understand how to enforce conditions and handle errors in their contracts.

## Features

- **Set Value Function**: Allows setting a value with checks to ensure the value is greater than zero and different from the current value.
- **Perform Division Function**: Performs division with checks to prevent division by zero and ensure the numerator is divisible by the denominator.

## Usage

1. **Deploy the Contract**: Deploy the `ErrorHandlingContract` to your preferred Ethereum network.
2. **Set Value**: Call the `setValue(uint _value)` function with a positive value to set the contract's `value`.
3. **Perform Division**: Call the `performDivison(uint _numerator, uint _denominator)` function with valid numerator and denominator values to get the division result.

## Error Handling

- **`require()`**: Used to validate that input values meet certain conditions (e.g., non-zero, non-division by zero).
- **`assert()`**: Ensures that certain conditions that should never occur are checked (e.g., new value is different from the current value).
- **`revert()`**: Stops execution and returns an error message if specific conditions are not met (e.g., numerator is not divisible by denominator).

## License

This project is licensed under the MIT License.

## Author

Ekta Mall

## GitHub Repository

https://github.com/EktaMall/ETH-AVAX-Assessment
