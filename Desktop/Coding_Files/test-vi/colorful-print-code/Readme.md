## What is this code about?

**This code prints 'colorful' in different colors which loops forever**


```
What all you need for this program to run:
    - Python
    - IDE
```

```python
# Importing Random and Time (They are default modules so there is no need to download them)
import random
import time

# The input takes the value what you want to print
text = str(input('What do you want to print: '))

# This is the while loop, to make our code run forever
while 1:
    # declaring a as 1
    a = 1
    
	#   # checks if a is 1, if yes, then it prints the text in Red colourChecks if a is 1, if yes, then it prints the text in Red colour
    if a == 1:
        print('\033[1;31;1m' + text)
        # Pauses for 0.1 sec to avoid spamming the system
        time.sleep(0.1)
        # declares a as 2
        a = 2
        
    # checks if a is 2, if yes, then it prints the text in Green colour
    if a == 2:
        print('\033[1;32;1m' + text)
        # Pauses for 0.1 sec to avoid spamming the system
        time.sleep(0.1)
        # declares a as 3
        a = 3
        
    # checks if a is 3, if yes, then it prints the text in Yellow colour
    if a == 3:
        print('\033[1;33;1m' + text)
        # Pauses for 0.1 sec to avoid spamming the system
        time.sleep(0.1)
        # declares a as 4
        a = 4
        
    # checks if a is 4, if yes, then it prints the text in Blue colour
    if a == 4:
        print('\033[1;34;1m' + text)
        # Pauses for 0.1 sec to avoid spamming the system
        time.sleep(0.1)
        # declares a as 5
        a = 5
        
    # checks if a is 5, if yes, then it prints the text in Purple colour
    if a == 5:
        print('\033[1;35;1m' + text)
        # Pauses for 0.1 sec to avoid spamming the system
        time.sleep(0.1)
        # declares a as 6
        a = 6
        
    # checks if a is 6, if yes, then it prints the text in Cyan colour
    if a == 6:
        print('\033[1;36;1m' + text)
        # Pauses for 0.1 sec to avoid spamming the system
        time.sleep(0.1)
        # declares a as 1, to loop the program
        a = 1
```
