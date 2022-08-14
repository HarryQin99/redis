### Redis creates its own string lib called dynamic strings library

How it is better than string lib in c?
1. O(1) time complexity to get the len of strings
2. Highly avoid stackoverflow happens
3. It uses some allocate algos to reduce the chance to re-allocate memory
4. Binary safety
5. Provides a lots API to handle strings, easy to use and understand


 