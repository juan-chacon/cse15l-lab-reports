The command being researched in this lab will focus on ```grep```

All of the citations for this lab will are below, only ChatGPT was used.

![Image]proof.jpg

The first command I experimented with was ```grep -v``` , the examples are below.

```grep -v ".txt" res.txt > grep-res1.txt```

![Image]grep-v1pic.jpg

This command searches for lines that do not contain the given pattern. The res.txt file contains all of the directories in written_2.

Upon inspection on grep-res1.txt we can see the output above, as those files/directories do not have .txt in their title. 

For the next example of grep -v, I used ```grep -v "non-fiction" res.txt > grep-res2.txt```

This command searched through the res.txt file, which contains all of the directories in written_2, and printed out directories/files that do not have the word non-fiction in them.

![Image]grep-v2pic.jpg


The next command tested was the ```grep -c command```

The command ran was ```grep -c "What" res.txt``` and it printed out 45.

This command searched through the res.txt file and printed out the number of lines that contain the word "What".

![Image]grep-c1.jpg

Another example of the same command was when I tried running ```grep -c "Bahamas" res.txt```

After running this command, it searched res.txt and printed out 4, which means that only 4 lines contain the word "Bahamas" in their title/

![Image]grep-c2.jpg

The next command being ran is the ```grep -l``` command.

This command searches for the given pattern in a file and only displays the filename that contains the given pattern, for example.

```grep -l "In" written_2/non-fiction/OUP/Abernathy*```

The command above will search through that given directory and print out only the filename that contains the given pattern, which in this case is "In". The results can be seen below

![Image]grep-l1.jpg

Another example of the command is ```grep -l -r "visit" written_2/```

This command works the same way as the one below but it searches for files that have the word "visit" instead of "in"

![Image]grep-l2.jpg

The final command being tested is the ```grep -n``` command.

This command prints out the lines in the given path that do  contain the given pattern, it's very similar to the ```grep -c``` command which gives you the number of lines that contain that pattern.

An example of the command that I ran would be ```grep -n "Bahamas" res.txt```

This command will output 4 files, with the given line, since those 4 contain the pattern "Bahamas"

![Image]grep-n1.jpg

Another example of this command is ```grep -n "What" res.txt```

The results would be 

![Image]grep-n2.jpg

 
