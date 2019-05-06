

# Morse_Code_Translator-
Morse code is a method of transmitting text information as a series of on-off tones, lights, or clicks that can be directly understood by a skilled listener or observer without special equipment.
# Encryption:
 
1) In case of encryption i extract each character (if not a space) from a word one at a time and match it with its corresponding morse code stored in whichever data structure i have chosen(if you are coding in python, dictionaries can turn out to be very useful in this case).</br>

2) Store the morse code in a variable which will contain our encoded string and then i add a space to our string which will contain the result.</br>

3) While encoding in morse code i need to add 1 space between every character and 2 consecutive spaces between every word.</br>

4) If the character is a space then add another space to the variable containing the result. i repeat this process till i traverse the whole string.</br>



# Decryption:
 
1) In case of decryption, i start by adding a space at the end of the string to be decoded (this will be explained later).</br>

2) Now i keep extracting characters from the string till i are not getting any space.</br>

3) As soon as i get a space i look up the corresponding English language character to the extracted sequence of characters (or our morse code) and add it to a variable which will store the result.</br>

4) Remember keeping track of the space is the most important part of this decryption process. As soon as i get 2 consecutive spaces i will add another space to our variable containing the decoded string.</br>

5) The last space at the end of the string will help us identify the last sequence of morse code characters (since a space acts as a check for extracting characters and start decoding them).</br>

