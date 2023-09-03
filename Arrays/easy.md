#### Two Number Sum
Write a function that 
- takes in a non-empty array of distinct integers and an integer representing a target sum
- If any two numbers in the input array sum up to the target sum, the function should return them in an array, in any order.
- If no two numbers sum up to the target sum, the function should return an empty array.
```
def twoNumberSum(array, targetSum):
  return []
```
- You can't add a single integer to itself in order to obtain the target sum
- You can assume that there will be at most one pair of numbers summing up to the target sum.

#### Valid Subsequence
- Given two non-empty arrays of integers
- Write a function that determines whether the second array is a subsequence of the first one.
- A subsequence of an array is a list of numbers that are in the same order as in the array.
- For example: `[1,3,4]` and `[2,4]` are both subsequences of `[1,2,3,4]`
```
def isValidSubsequence(array, sequence):
  return False
```

#### Sorted Squared Array
Write a function that 
- takes in a non-empty array of integers that are sorted in ascending order
- and returns a new array of the same length with the squares of the original integers also sorted in ascending order.
```
def sortedSquaredArray(array):
  return []
```

#### Tournament Winner
- There's an algorithms tournament taking place.
- Teams of programmers compete against each other to solve algorithmic problems as fast as possible.
- Teams compete in a round robin, where each team faces off against all other teams. 
- Only two teams compete against each other at a time,
- For each competition, one team is designated the home team, while the other team is the away team. 
- In each competition there's always one winner and one loser; there are no ties. 
- A team receives 3 points if it wins and 0 points if it loses. 
- The winner of the tournament is the team that receives the most amount of points.

---

- Given an array of pairs representing the teams that have competed against each other
- And given an array containing the results of each competition,
- Write a function that returns the winner of the tournament.
```
def tournamentWinner(competitions, results):
  return ""
```
- The competitions 2D-array has elements of the form `[homeTeam, awayTeam]`, like `["Python", "HTML"]` or `["HTML", "C#"]`.
- `results[i]` contains the winner of `competitions[i]` 
- `results[i] = 1` means that the home team won. Otherwise `results[i] = 0`
- It's guaranteed that exactly one team will win the tournament
- It's guaranteed that each team will compete against all other teams exactly once.
- It's guaranteed that the tournament will always have at least two teams.
- Example Input:
```
competitions = [["HTML", "C#"], ["C#", "Python"], ["Python", "HTML"]]
results = [0, 0, 1]
```
- C# beats HTML, Python beats C#, and Python beats HTML.
- HTML - 0 points, C# - 3 points, Python - 6 points.
- Example Output:
```
"Python"
```
