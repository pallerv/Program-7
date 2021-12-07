# Program-7
# Purpose: This program is takes a file containing the names and average rebounds of basketball players during the 2020-21 season. Sorts the data by the alphabetical oreder of the player names, then searches for the average rebounds of a given player using a binary search method. The user enters the name of the desired player.

# Input: Take in a file called "centers_rebs_20_21.txt" that contains the data. Later, take in player names entered by the user.
 
# Processing: Declare two parallel arrays in the main fucntion, one for the names and one for the average rebounds of the player, then store the data in them. A print function prints out the data. Then a function sorts the names array in alphabetical order of the names, with the average rebounds array changing accordingly. The data is printed again after it's been sorted. In the main function, write a loop to ask the user for a player name. A search funciton takes in the name and finds the index of it in the array using a binary search. It then returns the matching average rebounds that player, and it is printed out in the main funciton. This continues until the user enters "-1".
 
# Output: The data is printed out once at the beginning, than again after it's sorted. The matching average rebounds of players are printed based on what names the user enters.
