# Blockchain_Challenge
# Blockchain Development Challenge (Go)

Welcome to the Blockchain Development Challenge! This project aims to help you understand and implement core blockchain concepts using Go.

## Objective

Your task is to complete the implementation of a basic blockchain system. You'll work on creating blocks, handling transactions, and maintaining the integrity of the blockchain.

## Getting Started

1. Fork this Replit project to create your own copy.
2. Read through the code in the `blockchain` folder and `main.go` to understand the structure.
3. Implement the missing functions marked with `TODO` comments.
4. Test your implementation by running the `main.go` file.

## Files to Work On

- `blockchain/block.go`: Implement block creation and hash calculation.
- `blockchain/transaction.go`: Implement transaction creation and validation.
- `main.go`: Create the blockchain, add transactions, and test your implementation.

## Requirements

1. Implement the `CreateBlock` function in `block.go`.
2. Implement the `CalculateHash` function in `block.go`.
3. Implement the `CreateTransaction` function in `transaction.go`.
4. Implement the `ValidateTransaction` function in `transaction.go`.
5. In `main.go`, create a genesis block, add transactions, and create additional blocks.

## Tips

- Use the provided `calculateSHA256` function in `block.go` to help with hash calculation.
- Ensure that each block's `PreviousHash` correctly points to the hash of the previous block.
- Implement proper validation for transactions based on their type and amount.

## Evaluation Criteria

- Correct implementation of blockchain and block creation logic.
- Proper handling of transactions (deposit, withdraw, transfer).
- Accurate use of hashing to maintain blockchain integrity.
- Clean and readable code with appropriate comments.

Good luck, and happy coding!
