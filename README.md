This repository will demostrate different ways to extract unique user IDs from a file.

## Assumptions

- Characters in these IDs: only alpha and numeric character a-z|A-Z|0-9, which is 62 chars in total. 
- Length of a single ID: Let’s assume the length would be 7 chars for simplicity.  

With the two assumptions, the total number of uniqe user IDs is $62^7 = 3,521,614,606,208$, which is a huge number.


## Restrictions

- The input file is too big to fit in a the memory of a single machine.  
- Even, the total unique IDs are also too big to fit in the memory.  
