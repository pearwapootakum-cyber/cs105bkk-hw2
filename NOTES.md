# HW2 notes

Answer each question in a few sentences. Be specific: name the function, the error or the command.

## What did you try?
I implemented the required functions in errors.py, event.py, and club.py. I worked on creating events, signing up members, cancelling sign-ups, managing the waitlist, and handling chat commands. I also used pytest to check my code.

## What broke, and how did you fix it?
When I ran pytest, one test failed in attendance() because Counter was not defined. I fixed it by importing Counter from the collections module at the top of club.py. After that, I ran the tests again to check the fix.

## What would you do differently next time?
Next time, I would plan the structure of my code before starting. I would think about how the functions in event.py and club.py work together first, so it would be easier to organize the code.