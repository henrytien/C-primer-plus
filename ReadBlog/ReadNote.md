# read blog note

[How To Read Source Code](https://github.com/aredridel/how-to-read-code/blob/master/how-to-read-code.md)

- Look for guards and coercions
- Look for defaults
- Look for layers
- Look for tracing
- Look for reflexivity
- Look at lifetimes
  > Who initializes this?  
When does it change?  
Who changes it?  
Is this information somewhere else in the mean time? 
Is it ever inconsistent?  
Somewhere, someone typed the value you see into a keyboard, generated it from a random number generator, or computed it and saved it.    
Somewhere else, some time else, that value will affect some human or humans.   Who are these people?    
What or who chooses who they are?  
Is that value ever going to change?  
Who changes it?  

- Look for hidden state machines
- Look for common operations