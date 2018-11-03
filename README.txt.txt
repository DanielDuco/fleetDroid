Problems:
- I can't load the vehicleType images, but with an example picture (on a different server) it works

1. Describe possible performance optimizations for your Code. 
- The code could be more dynamic (look at the part with the TextViews, it could be done with an ArrayList).
- Otherwise the code could be optimized for a special CPU (like the Snapdragon 845). 
- How to get a perfectly fitting code:
-- Check the size of the cachelines
-- Check the size of the used datatypes
-- Place the attributes/objects in order, that they fill up the cachelines (important: without overflow)

2. Which things could be done better, than you’ve done it?
- The code could be more dynamic (look at point 1)
- Instead of adding markers in the jsonParse()-Method, I could wait for response in the main-task and add them there