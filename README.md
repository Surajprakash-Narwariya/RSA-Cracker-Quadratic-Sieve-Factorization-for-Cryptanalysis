# RSA-Cracker: Quadratic Sieve Factorization for Cryptanalysis

**RSA-Cracker** is a powerful and sophisticated tool that implements the **Quadratic Sieve** algorithm to factor large integers, effectively exposing vulnerabilities in **RSA encryption** systems.

## How It Works

The Quadratic Sieve algorithm operates through the following key steps:

1. **Finding Congruences of Squares**: The algorithm searches for numbers that, when squared, are congruent to the target number modulo a given base. This process identifies potential factors.
  
2. **Linear Algebra Techniques**: Once congruences are identified, linear algebra methods are applied to create a system of equations that can be solved to extract the factors of the target number.

By efficiently breaking the modulus of RSA public keys, **RSA-Cracker** illustrates how cryptanalysis can be utilized to recover private keys, thereby demonstrating the inherent weaknesses in the security of traditional encryption methods.

## Applications

- **Cryptanalysis**: The primary application of **RSA-Cracker** is to demonstrate how vulnerabilities in RSA encryption can lead to the recovery of private keys, emphasizing the risks associated with relying on large integer factorization for security.
  
- **Educational Resource**: This project serves as a valuable educational tool for researchers and students alike, providing insights into the mathematical foundations of cryptography and the practical applications of number theory in cybersecurity.

- **Security Enhancement**: By highlighting the weaknesses in RSA encryption, **RSA-Cracker** encourages the development of more robust encryption methods that can withstand advanced factorization techniques, ultimately contributing to stronger security protocols.
