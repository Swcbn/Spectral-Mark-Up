To begin a file, you type the name of the file normally, then put dashes at least as far as the title goes. Here's an example - 
Spectral Mark Up
-----------------
To style, you put it in parentheses, then add your styles like italics, bold, font, font size, font color, underline, strikethrough, etc.
Here's an example - 
(fontTimesNewRoman, size30, bold)
Styles will keep going untile you put (clearFormatting).
To restore just specific formatting section, you type [style]Normal
Here's an example that only restores the font after it was styled to TimesNewRoman.
(fontNormal)
You may combine tags by using commas. For example - 
(fontTimesNewRoman, size 40, script)
Comments are done with hashtags, one hashtag for each line of comments. Say you need five lines to comment, you just put - 
##### [line](comment)
      [line](comment)
      [line](comment)
      [line](comment)
      [line](comment)
      [line](markup)
