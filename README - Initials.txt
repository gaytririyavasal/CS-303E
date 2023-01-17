PROJECT DESCRIPTION AND GUIDELINES PROVIDED ON ASSIGNMENT INSTRUCTIONS

Your task is to write a program that prints your initials in large letters. For example, my initials are W.D.Y. So I might print these out as shown below. If your name has less than 3 initials, pad on the right with X's. For example, if your initials are A.B., you should display A.B.X. If you have more than 3 initials, you can give them all or stop at 3; that's your choice.
  WW        WW      DDDDDDDD          YY        YY      
  WW        WW      DDDDDDDDDD         YY      YY       
  WW        WW      DD       DD         YY    YY        
  WW        WW      DD        DD         YY  YY         
  WW        WW      DD        DD          YYYY          
  WW   WW   WW      DD        DD           YY           
  WW  WWWW  WW      DD        DD           YY           
  WW WW  WW WW      DD       DD            YY           
  WWWW    WWWW  ..  DDDDDDDDDD    ..       YY       ..  
   WW      WW   ..  DDDDDDDD      ..       YY       ..  

Note that the big "W" is made of uppercase "W"s, the big "D" is made of uppercase "D"s, and so on. Each letter should be exactly 12 characters wide and 10 lines high, with one exception: if one of your initials is "I" make it 6 characters wide, rather than 12, with a serif at the top and bottom. (A serif is that wider area at the top and bottom.) The width of the line making up each letter generally should be 2 characters. (Do your best for curved letters, but don't stress it!) Each letter should be followed by a period, drawn using four "." characters, as shown above. There should be two empty columns of spaces to the left and to the right of each letter and period (including the final period). Notice that this means that every line should be exactly the same length, so pad on the right with blanks as needed. You won't see this on the screen, but it would be helpful if, for example, you or someone else needed to modify your program by adding another letter on the right.
Also, there should be an empty line at the top and one at the bottom. (You can create an empty line with the command print(). It doesn't have to contain any spaces.)
It is very important to follow these directions exactly. One of the most important skills of programming is to be able to implement a specification given to you by someone else. You should follow the specification exactly, unless you're explicitly given freedom to improvise. If a specification is ambiguous, you should talk to your client (us) to clarify. That's called "requirements analysis" (among other things). So, if something is unclear, ask (preferably on Piazza). If you don't follow the specification, don't be surprised when you lose points.
Note that your output won't look right unless you are using a fixed-width font. Most editors allow you to choose a font.
