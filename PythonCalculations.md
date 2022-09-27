# Using Nano Text Edit to Write a Python Script for Running it on the Terminal

To create a Python script in Nano textedit, use:
```bash
#! /usr/bin/env python
```

Linux shortcut for new line:
```bash
\n\n 
```

To run a python program not in your path, use:
```bash
./name_script.py
```
To take input for a new sequence from command line when a program is running, use:
```
DNASeq = input('Enter a DNA Sequence:')
```
To list the complementing bases, use:
```bash
Comp = DNASeq.replace('A', 't')
Comp = Comp.replace('T', 'a')
Comp = Comp.replace('C', 'g')
Comp = Comp.replace('G', 'c')
```

To flip the reverse complimentary, use:
```bash
print('The reverse complimentary sequence is:', Comp[::-1], '\n')
```
