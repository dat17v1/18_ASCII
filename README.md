# #18 Ascii Codes Explained
Computers deal with numbers, not letters or punctuation, and so to get them to work with text we need to represent each and every character as a number.

The text files that you read and write are actually stored, loaded into memory and manipulated as a sequence of numbers. When the computer displays the data on screen as text, it changes the numbers into characters so that humans can understand it.

In order for text files to be reliably stored and processed by computers, it is important that they all interpret the data in the same way. To achieve this, a standardised mapping was created that defined what numbers should be used to represent all the characters in the english language. This mapping was called the American Standard for Information Interchange, or ASCII for short.

## Lower Ascii Table

The Ascii table is split into two sections, the lower ascii table and the upper ascii table. The lower ascii table defines all numbers beteen 0 and 127 inclusive. This is the officially standardised section of the Ascii table and represents all the most common characters.
The numbers from 0 to 31 inclusive represent non-printing characters, meaning characters that are not directly displayed. These characters control how the data should be interpretted. They were designed for when text was processed by teletype terminals and as such needed characters to represent actions such as ringing an audible bell, and signalling the beginning or end of a data transmission. Although a lot of these characters are no longer of any use, some of them have become common place.

The carriage return is the character used by the Macintosh to represent a new line. On UNIX (and in some Mac OS X text files) the line feed is the standard way of designating a new line. On Windows, both a carriage return AND a line feed are used as a pair! The other commonly used control characters include NULL, which often indicates the end of a string of text, tab which is used to assist the layout of text by indenting it and backspace which deletes the previous character.

All the rest of the characters above 31 in the lower ascii table are printable, except for forward delete, an apparently late addition which, means to delete the next character.

Lower Ascii Table
![Lower Ascii Table]()

## Upper Ascii Table

The upper Ascii table has not been officially standardised, and tends to vary from computer to computer and from font to font. Some characters are more standard than others, and your milage may vary, but here's the table for the Macintosh Courier font.

Upper Ascii Table
![Upper Ascii Table]()



&copy; http://www.tntbasic.com/learn/help/guides/asciicodesexplained.htm
