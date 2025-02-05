# PlayfairCipher
This repository provides an implementation of the Playfair Cipher, a classic encryption technique used for encoding and decoding text.

<b>Introduction</b><br>
The Playfair Cipher is a digraph substitution cipher. It encrypts pairs of letters (digraphs) instead of single letters.The cipher uses a 5x5 matrix filled with letters of the alphabet, where each letter appears only once. The matrix is created using a keyword, which helps in determining the positions of the letters.<br>

<b>Playfair Cipher Rules:</b><br>
A 5x5 matrix is created using a keyword and the remaining letters of the alphabet (excluding J, which is combined with I).<br>
If a digraph contains the same letter twice (e.g., "LL"), an 'X' is inserted between the letters.<br>
Depending on the position of the digraph's letters in the matrix, different rules are applied to encrypt or decrypt:<br>
If the letters appear in the same row, each letter is replaced by the letter to its right.<br>
If the letters appear in the same column, each letter is replaced by the letter below.<br>
Otherwise, each letter is replaced by the letter in its row and column that is at the other letter's position.<br>

<b>Setup and Requirements</b><br>
To run the Playfair Cipher implementation on Google Colab, no installation of external libraries is required. 
Click the link here to access and run the code on Google Colab <a href="https://colab.research.google.com/github/nidhipai78/PlayfairCipher/blob/main/PlayfairCipher.ipynb">Click Here</a><br>




