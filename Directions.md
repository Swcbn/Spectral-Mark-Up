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
Scripts are executed using the script tag. First, you have to put an opening (script) tag. Then you put a secondary (script[script language]) tag. Scripts can be specified, as well. To specify a version of a language, put a comma, then, if it's a number, put "v.[version number]" If it is a title (for, perhaps, a linux distro), put "t.[distro name].[version title]. Linux distros always use this as the script language - 
(script*nix)
Here are some examples - 
(scriptPython, v.3)
(scriptPython)
(script*nix, t.Ubuntu.XenialXerus)
To end the Script, you use (end).
To end the Markup file, you use (end).
Then you put the same number of dashes as you did at the top.
Then you type the name of the file as you did at the top.

*Note - spaces in, after, and before tags are treated as whitespace and do not change anything about the file's content.
For more information, see the folder dubbed "Examples."