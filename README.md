# Aicte-Project-Stenography:
## Overview:
A basic project utilizing python to explore concepts related to data encryption and decryption affiliated with image inclusion to enhance security measure. 

The most common forms of computer security are known as cryptography. System architects employ these strategies to make information secret to frustrate attackers.
A cipher is an algorithm that converts plain text into ciphertext, which is nonsense unless you have a key that lets you undo the cipher. The process of making text secret is called encryption, and the reverse process is called decryption.
Cryptographic techniques rely on keys that are known by both the sender and recipient. The sender encrypts a message using a key, and the recipient decrypts it using the same key.
Key exchange uses an algorithm that lets two computers agree on a key without ever sending one, using one-way functions (mathematical operations) that are easy to do in one direction, but hard to reverse.
Keys that can be used by both sender and receiver, to encrypt and decrypt messages, are called symmetric keys because the key is the same on both sides.
Asymmetric encryption uses two different keys, most often one that is public and another that’s private. Senders can encrypt a message using a public key that only the recipient, with their private key, can decrypt.
## Screenshots of code:
<img width="959" alt="3" src="https://github.com/user-attachments/assets/fa526a76-3bc8-41cb-884a-c71683c50669" />
<img width="946" alt="2" src="https://github.com/user-attachments/assets/305fc312-56ab-42b0-ac71-1ef0a6a0124a" />
<img width="491" alt="1" src="https://github.com/user-attachments/assets/90b705a0-0f48-41d6-88d3-b353510b1a85" />

## Installation:
### Prerequisites
1. Install [python](https://www.python.org/downloads/), which is required to manage the project's dependencies.
2. Optional -> Install pycharm or any other IDE. [pycharm](https://www.jetbrains.com/pycharm/download/?section=windows)

### Steps to Run the Project
1. Clone the repository to your local machine.
2. Navigate into the project folder.
3. Open 'stego.py' file containing the python code using pycharm IDE. Otherwise open python shell and open the file stego.py
4. Install opencv-python module using pycharm for running the co-related library in the program. Or else donwload file from web and install it via cmd (command: pip install opencv-python)
5. Compile the 'stego.py'. Ensure the file path of the photo you are using for the project exsists within the code project folder (same place where your stego.py file is stored). Use only the photo's file name.
6. After successfully running the code an encryoted file is created in the same file format as your photo file . Do not delete the encrypted file otherwise decrpytion will fail.
