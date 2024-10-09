# Blockchain_Challenge
## Welcome to the Blockchain Development Challenge! An implementation of core blockchain concepts using Go.

## Objective

Your task is to complete the implementation of a basic blockchain system. You'll work on creating blocks, handling transactions, and maintaining the integrity of the blockchain.

## Getting Started

1. Fork this project to create your own copy of the repository.
2. Use GitHub Codespaces:
    - Click on the green Code button in your forked repository.
    - Select Codespaces and choose "Create codespace on main" to open your development environment.
5. Once the Codespace is ready, read through the code in the blockchain/ folder and main.go to understand the structure.
6. Implement the missing functions marked with TODO comments.
7. Test your implementation by running the main.go file inside GitHub Codespaces.

## Steps to Follow

1. Fork the repository and set up your environment using GitHub Codespaces.
2. block.go: Implement the block creation logic and hash calculation.
3. transaction.go: Handle transaction creation and validation.
4. main.go: Test the blockchain by adding a genesis block, creating transactions, and adding additional blocks.
5. Run the code within GitHub Codespaces to test your implementation.

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

## Submission Guidelines
- After completing the challenge, submit the link to your forked GitHub repository in the LMS submission link text box.

## Evaluation Criteria

- Correct implementation of blockchain and block creation logic.
- Proper handling of transactions (deposit, withdraw, transfer).
- Accurate use of hashing to maintain blockchain integrity.
- Clean and readable code with appropriate comments.

Good luck, and happy coding!
