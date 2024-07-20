# AES-128

## Description

This project implements the AES-128 encryption model using the CTR mode. It also includes a simulation of an attack to demonstrate the viability of the AES-128 encryption against potential attacks.

## Features

- **Encryption/Decryption**: Uses the AES-128 model to secure data.
- **Attack Simulation**: Performs a simulation to test the robustness of the algorithm against attacks.
- **Nonce Generation**: Generates random nonce values for the CTR mode.

## Compilation

To compile the project, use the provided `Makefile`. Run the following command in the project directory:

```sh
make
```

## Commands

- `./main -h`: Displays the help for available commands.
- `./main -nonce`: Generates a random nonce.
- `./main "secret_key_16_chars" "nonce_16_chars" -e input_file -out output_file`: Encrypts or decrypts a file using AES-128. Specify the input file, and optionally designate an output file with the `-out` option.
- `./main "secret_key_16_chars" "nonce_16_chars" -a input_file`: Performs an attack simulation on the specified file.

## Author

Group of students
