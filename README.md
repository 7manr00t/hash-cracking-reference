

# Hash Cracking Reference

A practical reference on cryptographic hashing — how 
hashing algorithms work, why legacy algorithms fail, 
and how attackers exploit weak implementations.

---

## Topics & Tools



![Security+](https://img.shields.io/badge/Security%2B-SY0--701-red)




![TryHackMe](https://img.shields.io/badge/TryHackMe-Crack_the_Hash-212C42)




![Cryptography](https://img.shields.io/badge/Topic-Cryptography-blue)





---

## What This Covers

- How hashing algorithms work — MD5, SHA1, SHA256, bcrypt
- Why MD5 and SHA1 are broken for password storage
- Dictionary attacks, rainbow table attacks, brute force
- Why salting matters and how it breaks rainbow tables
- Algorithm comparison — which to use and when

---

## Files

| File | Description |
|------|-------------|
| `algorithms.md` | MD5, SHA1, SHA256, bcrypt side-by-side comparison |
| `attack-types.md` | Dictionary, rainbow table, brute force explained |
| `wordlists/common.txt` | Curated wordlist used in demonstrations |

---

## Background

Most legacy systems — including those in banking and 
fintech — still store passwords using MD5 or SHA1. 
This reference documents the technical reasons those 
algorithms fail, how quickly they can be exploited, 
and what the secure alternatives are.

Written during hands-on lab work covering TryHackMe 
*Crack the Hash* and *Hashing — Crypto 101*, mapped 
to Security+ Domain 2 objectives.

---

## Key Findings

- An unsalted MD5 hash is cracked in under a second 
  against rockyou.txt
- MD5 produces hash collisions — two different inputs 
  can generate the same output, breaking integrity
- bcrypt and Argon2id are the only production-safe 
  options for password hashing
- Hash-related vulnerabilities consistently score high 
  on CVSS because the impact is always credential 
  exposure
---

## How to Use

Browse the files directly on GitHub — 
no installation needed.

---

## Connect

- Instagram: [@7man.r00t](https://instagram.com/7man.r00t)
- LinkedIn: [Abdelrahman Elsayed](https://www.linkedin.com/in/abdelrahman-ahmed-elsayed-612732397?utm_source=share_via&utm_content=profile&utm_medium=member_android)
