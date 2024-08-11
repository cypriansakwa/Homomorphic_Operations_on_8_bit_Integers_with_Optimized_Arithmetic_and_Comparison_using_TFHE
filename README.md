This project outlines how to use the TFHE library to execute various homomorphic operations on 8-bit integers. 
The code demonstrates efficient arithmetic (addition, subtraction, multiplication, division, remainder, and bitwise shifts) 
and comparison operations (equality, inequality, greater than, and less than) on encrypted integers.

## Overview
The code employs TFHE (a library for fully homomorphic encryption) to:
1. Set up configuration of cryptographic parameters and Generate necessary Keys
2. Encrypt 8-bit integer values for secure computation.
3. Execute both arithmetic and bitwise operations on encrypted values.
3. Decrypt the results to ensure they match the cleartext computations.

## Steps
1. Set Up Configuration and Generate Keys: The TFHE configuration is set to the default parameters. Keys for encryption and decryption are generated, and the server key is set up.
2. Encrypt Clear Values: Define clear values and encrypt them using the client key.
3. Perform Computations: Execute the following operations on encrypted values:
   a) Arithmetic Operations: Addition, subtraction, multiplication, division, and remainder.
   b)  Bitwise Operations: AND, OR, XOR, negation, and NOT.
   c) Shifts: Left and right shifts.
   d) Comparison operations:
       Equality (==)
       inequality (!=)
       Greater than (>)
   Less than (<)
4. Decrypt Results and Verify: Decrypt the results of operations and compare them to the predicted results from cleartext computations.
   If all computations are right, print the success message.
5. The code
## Requirements
1. Ensure you have Rust installed.
2. Add tfhe to your Cargo.toml file.
3. Run cargo run in your terminal.
git clone https://github.com/cypriansakwa/Homomorphic_Operations_on_8_bit_Integers_with_Optimized_Arithmetic_and_Comparison_using_TFHE.git
cd Homomorphic_Operations_on_8_bit_Integers_with_Optimized_Arithmetic_and_Comparison_using_TFHE
