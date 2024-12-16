# kronos-patriot-puzzle
A secret challenge for Ian: decrypt the Kronos-Patriot-Puzzle 🕒. Find the hidden letter using RSA encryption and a shifted alphabet. Do you have what it takes?


# Kronos-Patriot-Puzzle 🕒🦸‍♂️🏀

**Welcome, Ian, to YOUR Kronos-Patriot-Puzzle!** 

This challenge is tailor-made for a genius-in-the-making who loves *The Incredibles*, Giannis Antetokounmpo, and college football. You’ve been chosen to crack the **ultimate secret code** using your wits and a bit of RSA encryption. Are you ready? 🕶️✨

If you're new to GitHub.... GitHub is a platform for storing, sharing, and collaborating on code. It uses Git, a version control system, to track changes and manage different versions of your projects. Developers use it to host repositories, collaborate with others, and showcase their work. (Don't worry about this info it's just a fun fact).

---

## 🧩 **What’s the Mission?**

Kronos Antetokounmpo has encrypted a message, and only you can unlock it. Your task is simple but requires focus:

1. **Break the encryption** to find the secret number.
2. **Match the number** to the shifted alphabet to discover the hidden letter.
3. **Claim victory** and prove you’re the ultimate MVP—Most Valuable Problem-Solver!

---

## 🛡️ **Learn Something New: RSA Encryption**

### 🏀 **What’s RSA?**  
RSA encryption is the online world’s super-secret locker code. It was invented in 1977 by Rivest, Shamir, and Adleman (RSA) to protect sensitive information like bank details, passwords, and secret messages.

### ⚙️ **How Does It Work?**
- RSA uses two special keys: one **locks** the message (encrypts it), and the other **unlocks** it (decrypts it).  
- Encrypting a Message: You lock it with a public key—a magical number shared with the world.
- Decrypting the Message: You unlock it with a private key—a secret number only you know.
- The Twist: It’s practically impossible to crack without knowing the prime numbers behind the keys. That’s the magic of math! ( The magic lies in **big prime numbers**. Finding the key without knowing the primes is almost impossible—like beating Giannis in a 1-on-1).

---
## 🔓 **The Puzzle: Decode the Hidden Letter**
### 🔍 **Steps to Decode the Letter**
**1. Your Challenge! **

Here is the alphabet you are used to seeing. 

Imagine that each letter had a number associated with it to determine what place it falls in the alphabet.

(e.g. (A = 0, B = 1 , C = 2  D = 3, ..., Z = 25)) 

Except 1 thing... Kronos has shifted these letters 17 steps to the right meaning that now A = 17 B = 18, C = 19 and so on. Now Use this knowledge to decrypt the message containing the letter to the codex with the blob of numbers below:

15 5 11 8 2 21 10 10 21 8 10 5 10 24 21 19 5 20 21 14 25 9 0 11 9 10 1 25 20 20 25 4 23 10 5 23 21 10 15 5 11 8 22 25 4 17 2 2 21 10 10 21 8 22 5 2 2 5 13 10 24 21 25 4 9 10 8 11 19 10 25 5 4 9 18 21 2 5 13 15 5 11 8 23 5 17 2 20 21 19 5 20 21 10 24 21 25 4 20 21 14 11 9 25 4 23 3 5 20 11 2 17 8 17 8 25 10 24 3 21 10 25 19 10 5 20 21 10 21 8 3 25 4 21 10 24 21 22 25 4 17 2 2 21 10 10 21 8 17 22 10 21 8 9 5 2 12 25 4 23 10 24 21 3 5 20 11 2 17 8 2 25 4 21 17 8 19 5 3 18 25 4 17 10 25 5 4 17 4 20 13 5 8 1 25 4 23 18 17 19 1 13 17 8 20 15 5 11 19 17 4 25 20 21 4 10 25 22 15 10 24 21 25 4 12 21 8 9 21 10 5 15 5 11 8 6 11 18 2 25 19 1 21 15 13 24 25 19 24 19 5 25 4 19 25 20 21 4 10 17 2 2 15 25 9 10 24 21 2 21 10 10 21 8 10 5 15 5 11 8 19 5 20 21 14


**2. Given your Private Key and Modulus Compute Modular Inverse using the Extended Euclidean Algorithm! **
   
Public key 𝐾 = 13457 
Modulus 𝑀 = 65537

GCD(65537,13457)


**3. Match the number you've calculated to the letter on the modified alphabet shifted by  17 to the right  in step 1 and  ooala you have your 4th letter to your codex!**

---

## 🏆 **Victory Is Yours!**

If you get stuck:


https://github.com/user-attachments/assets/43118a74-48f5-42f7-a494-5ae9ca8915ef
https://www.youtube.com/watch?v=bZ275aLiypo (5 minutes in they work one out :) ) Remember the answer is the INVERSE to your private key, where X*K Divided by your Modulus gives a remainder of 1 :D
