# Problem 217: Contains Duplicate

7/12/2025

## Thought Process
This was another for loop problem. This time, I knew I needed another List so that I am able to compare the two. I went for a list and then appending each element in the num List to my created List.

##  Initial Solution
I created my numList list, and traversed through the num list. I appended each num variable and checked to see if that variable was already in numList. If it was, the program would return True. If the entire for loop was run, I would return False. 

Initial solution - Time Limit Exceeded 

Complexity - O(n)

I ran into the issue of some of the test cases being too large (50000+ int variables in List). 

## Final Solution
I decided to use a hashset, which would allow for faster and more efficient sorting. So I used set() to create the set, and whenever I added the variables into the set, I used .add(). This allowed for faster runtime and for the program to be able to process large Lists. 

Final Solution - 19 ms

Complexity - O(n)

## Takeaways
I learned how to create a HashSet in Python and some basic methods I can use to modify and manipulate the Hashset. I also learned about the speed and efficiency of a HashSet being faster than that of a List. 