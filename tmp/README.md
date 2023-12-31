# How It Works
This utility encodes textual information into a sequence made up of the four nucleotides (adenine (A), guanine (G), thymine (T), and cytosine (C)) that make up DNA, allowing for the biologically-inspired storage of information. Conversely, it can decode a given DNA sequence back into human-readable text. The program represents each ASCII character as an 8-bit binary number and translates each pair of bits into a DNA base as follows:

00 -> A
01 -> T
10 -> G
11 -> C
Therefore, each character is encoded as a sequence of 4 DNA bases. For decoding, the program reverses this process, converting each set of four bases back into the corresponding ASCII character.

# Usage
Upon running the program, users will be prompted to choose one of the following options:
- Convert DNA sequences back to text (Option 1)
- Convert textual sequences to DNA (Option 2)
- Quit the program (Q)
To convert text to DNA, simply enter the text when prompted. To convert DNA back to text, enter the DNA sequence, ensuring it only contains the characters A, G, T, and C. If an invalid DNA sequence is entered, the program will prompt for re-entry. Users can quit the program at any time by pressing 'Q'.

# Example

<img width="496" alt="image" src="https://github.com/Synthia-Li/Decode-encode-Anything/assets/143859275/897a4bd6-e664-4e69-b8d7-cdbc0105a00b">
