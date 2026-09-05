# HIT137 – Group Assignment 2

This repository contains our solutions for both questions in HIT137 Group Assignment 2. The project includes the required Python programs, input files, and generated output files for each question.

## Repository Structure

```text
HIT137-Group-Assignment-2/
├── README.md
├── github_link.txt
│
├── Question1/
│   ├── cipher.py
│   ├── raw_text.txt
│   ├── encrypted_text.txt
│   └── decrypted_text.txt
│
└── Question2/
    ├── evaluator.py
    ├── input.txt
    └── output.txt
```

## Question 1 – Cipher

Question 1 focuses on creating a text encryption and decryption program.

The program:

* Reads the original text from `raw_text.txt`.
* Encrypts the text using the given `shift1` and `shift2` values.
* Saves the encrypted text in `encrypted_text.txt`.
* Decrypts the encrypted text.
* Saves the decrypted text in `decrypted_text.txt`.
* Checks that the decrypted text is the same as the original text.

### Running Question 1

Open a terminal inside the `Question1` folder and run:

```bash
python cipher.py
```

The program will ask the user to enter values for `shift1` and `shift2`. Both values should be non-negative integers.

## Question 2 – Mathematical Expression Evaluator

Question 2 focuses on building a mathematical expression evaluator using a recursive descent parser.

The program reads mathematical expressions from `input.txt`, processes them according to the required operator precedence rules, and writes the results and other required information to `output.txt`.

### Running Question 2

Open a terminal inside the `Question2` folder and run:

```bash
python evaluator.py
```

## Group Contributions

| Group Member | Contribution                                       |
| ------------ | -------------------------------------------------- |
| Sandesh      | Question 1 – Encryption                            |
| Aadesh       | Question 1 – Decryption                            |
| Aditya       | Question 2 – Mathematical Expression Evaluator     |
| Sherzod      | Question 1 – Verification, Integration and Testing |

The contribution details may be updated as the project progresses.

## Testing

Each part of the assignment will be tested separately during development to make sure it works as expected.

Once all parts are completed, we will combine the work and test the complete project to make sure the programs work together correctly and produce the required outputs.
