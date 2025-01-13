# Python Password Generator

A simple password generator with different preferences. You can either generate a completely random password, or insert your own keyword and randomize capitalization/generate random symbols next to it. If you have selected multiple preferences, a function makes sure that those preferences are met. For example, if you have selected that you will have numbers, symbols and capitalized letters, it WILL have all 3 if you choose a valid length for the password (long enough that the preferred symbols/letters/numbers can generate next to your keyword)

### If you want to insert your own keyword, you need to make sure that:
*  Your keyword is not longer that the selected length
*  You have enough space for the selected preferences. For example, if you have:
     * written a keyword that is 8 letters long (which does not include symbols OR numbers)
     * selected the length of the password as 9
     * selected that it should generate symbols and numbers next to it
*  The program will give you a warning, and the password will include either a random symbol or a random number next to it, but not both

![image](https://github.com/user-attachments/assets/55c33de5-78bd-4e7b-8dfd-fd127f110401)
