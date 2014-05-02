My Linux Shell Scripts
======================

This is a small collection of Linux shell scripts. Here's a
brief description of them:

* `ff` - stands for "file find". it's like find+grep, but uses a
  collection of tools to create an output that i like, showing
  the filename that was matched, the line number that matched, 
  and the text from the line that matched. if you use find+grep
  a lot, or perhaps `grep -r`, you might like this script.
* `explore` - prints lines before and after a regex match in a file.
  for instance, if a grep search matches line 50 in a file, and you
  specify that you want explore to show 10 lines around that match,
  explore will print lines 40 through 60.
* `glimpse` - this is an interactive shell script that combines `ff`
  and `explore` into one tool. when you first run it, it works like
  `ff`, as a find/grep tool. after it has found some matches it then
  works like `explore`, letting you poke around the files that were
  matched.


More Information
----------------

For more information, see my website at http://alvinalexander.com


