Simple Image Encryption Tool

📌 Overview
This is a basic Python program that performs image encryption and decryption using simple pixel manipulation techniques.
It supports:
- Swap operation → Shuffles pixel positions using a key.
- Add operation → Modifies pixel values using a mathematical operation.
-The same key must be used for encryption and decryption.

🛠️Tech Stack
-Python 3
-Pillow (Python Imaging Library fork)

🚀How It Works
-Swap:The positions of pixels are shuffled using a random sequence generated from a key.
-For decryption, the shuffle is reversed using the same key.
-Add:Adds a fixed value to each pixel’s RGB values (with wrap-around at 255).
-For decryption, the value is subtracted instead.

📚What I Learned
-How to read and modify image pixels using Pillow.
-How random number seeds can be used for repeatable encryption patterns. 
-Basics of reversible encryption using mathematical operations.
