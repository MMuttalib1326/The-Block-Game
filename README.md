# The-Block-Game
The citizens of Byteland regularly play a game. They have blocks each denoting some integer from 0 to 9. These are arranged together in a random manner without seeing to form different numbers keeping in mind that the first block is never a 0. Once they form a number they read in the reverse order to check if the number and its reverse is the same. If both are same then the player wins. We call such numbers palindrome.

for _ in range(int(input())):
    n=input()
    if n==n[::-1]:
        print("wins")
    else:
        print("loses")
