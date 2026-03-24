## 🕵️‍♂️ Encoder Decoder: Caesar Cipher

A sleek,noir-inspired web application for encrypting and decrypting messages using the classic Caesar Cipher algorithm. Built with a "Top Secret" aesthetic for the modern-day digital spy.


## ✨ Features
Real-time Encoding/Decoding: Watch your message transform as you type.
Interactive Cipher Wheel: Visualizes the alphabet shift (A → D, etc.) based on your key.Smart Key Handling: Supports shifts from 1 to 25 with easy-to-use increment buttons.
Noir UI: Custom-themed interface featuring scanlines, "Special Elite" typewriter fonts, and a "Gold on Charcoal" color palette.
Utility Tools: Quick-copy to clipboard, panel swapping (Encode ↔ Decode), and a "Clear All" function to destroy evidence.


## 🚀 Quick Start
Clone the repository or download the index.html file.
Open index.html in any modern web browser.
Select your Key: Choose a shift number (the default is 3, used by Julius Caesar himself).Type your message: Input your plain text to receive the secret code instantly.

## 🛠️ Technical Details
The project is a standalone single-page application (SPA) built using:
HTML5 & CSS3: Utilizing CSS Variables for theming and Keyframe Animations for the flicker/fade effects.
Vanilla JavaScript: No external libraries or frameworks required.
The Math: Uses the modulo operator to handle character shifting
            Cipher(x) = (x + n) mod 26
            Where x is the character index and n is the shift key.