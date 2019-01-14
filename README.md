This repository will demostrate different ways to extract unique user IDs from a file.

## Restrictions

- The input file is too big to fit in a the memory of a single machine.  
- Even, the total unique IDs are also too big to fit in the memory.  

## Assumptions

- Characters in these IDs: only alpha and numeric character a-z|A-Z|0-9, which is 62 chars in total. 
- Length of a single ID: Let’s assume the length would be 7 chars for simplicity.  

Note: With the two assumptions, the pool of uniqe user IDs could reach to $62^7 = 3,521,614,606,208$.
