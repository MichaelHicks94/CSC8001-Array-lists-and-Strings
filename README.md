# CSC8001-Array-lists-and-Strings

My second piece of coursework for CSC8001. The goal of this project was to write a program which read the content of a text file, picked out the words from the text file (while replacing all upper case letters with lower case ones), output the words to a .txt document called dictionary which contained a list of words from the input file in alphabetical order (one word per line, no duplication) with the number of times that word appears listed next to the word. The aims of this project were to extend the knowledge and understanding of array lists, extend our knowledge of the java.lang.String class and its methods, to gain experience at using I/O files in java and to learn about static methods and how to structure a Java program.

Specification:

Write a Java program to perform the following tasks:
1. Read the content of a text file;
2. Pick out all words within the text (by definition, a word is a string consisting only of
letters), replacing all upper case letters with lower case ones;
3. Produce a dictionary of the words appearing in the text (i.e., a list of the words in
alphabetical order, one word per line, without duplication);
4. Output the dictionary to another file.

For example, if the input file contains:

In the cool, cool breeze of the evening, the nightingale
sang 27 SWeeT songs.

The output file should contain:

breeze
cool
evening
in
nightingale
of
sang
songs
sweet
the

Methodology: 

Use a Scanner class to pick out strings which might be words. If the last
character in a string is a punctuation mark, remove it. For this exercise, the only punctuation
marks are ,;:.!? . All other characters must be letters in order that the string may be
accepted as a word. Use an ArrayList<String> to store and sort words. Remove
repetitions.

Enhancement: 

Print to the terminal window the dictionary, together with a column of
integers indicating how many times each word appears in the text. For example,

breeze 1
cool 2
evening 1
in 1
nightingale 1
of 1
sang 1
songs 1
sweet 1
the 3

In order to be able to align the counters nicely under each other, assume an upper bound for
the length of words (for example 30 characters).
