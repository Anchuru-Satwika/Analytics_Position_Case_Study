# Analytics Position Case Study

**ABC** is a real-money online gaming company providing multiplayer games such as Ludo. A user can register as a player, 
deposit money in the platform and play games with other players on the platform. 

- If he/she wins the game then they can withdraw the winning amount while the platform charges a nominal fee for the services.

- To retain players on the platform, the company ABC gives loyalty points to their players based on their activity on the platform.

- Loyalty points are calculated based on the number of games played, deposits and withdrawals made on the platform by a particular player.

The criteria to convert a number of games played, deposits and withdrawals into points are given below:"	


|Type of Action|Weightage per activity|Formulae|Eg.|
|---|---|---|---|
|Deposit of money on the platform|0.01|0.01 * Deposit Amount|0.01 * (1000 RS Deposit) = 10 Points|
|Withdrawal of money from the platform|0.005|0.005 * Withdrawal Amount|0.005 * (500 Rs Withdrawal) = 2.5 Points|
|How many more times did a player do deposit than withdrawal|0.001|0.001 * maximum of (#deposit - #windrawal) or 0|0.001 * max((5-3, 0)) = 0.001 * 2 = 0.002 points |
|Number of games played|0.2|0.2 * Number of Games Played|0.2 * (50 Total Games Played) = 10 Points|

			
**Final Loyalty Point Formula**

Loyalty Point = (0.01 * deposit) + (0.005 * Withdrawal amount) + (0.001 * (maximum of (#deposit - #withdrawal) or 0)) + (0.2 * Number of games played)

At the end of each month, total loyalty points are allotted to all players. Out of which the top 50 players are provided cash benefits."			
			
---

## Part A - _Calculating Loyalty Points_

On each day, there are 2 slots for each of which the loyalty points are to be calculated: 
- S1 from 12 am to 12 pm 
- S2 from 12 pm to 12 am"			
Based on the above information and the data provided answer the following questions:

1. Find Playerwise Loyalty points earned by Players in the following slots:-
- 2nd October Slot S1
- 16th October Slot S2
- 18th October Slot S1
- 26th October Slot S2
2. Calculate overall loyalty points earned and rank players based on loyalty points in October. 


`In case of a tie, the number of games played should be taken as the next criteria for ranking.`

3. What is the average deposit amount?
4. What is the average deposit amount per user in a month?
5. What is the average number of games played per user?"			


## Part B - _How much bonus should be allocated to leaderboard players?_

After calculating the loyalty points for the whole month find out which 50 players are at the top of the leaderboard. The company has allocated a pool of Rs 50000 to be given away as bonus money to the loyal players.

Now the company needs to determine how much bonus money should be given to the players.

- Should they base it on the number of loyalty points? 
- Should it be based on the number of games? Or something else?

That’s for you to figure out.

Suggest a suitable way to divide the allocated money keeping in mind the following points:
1. Only the top 50 ranked players are awarded a bonus.

Part C
- Would you say the loyalty point formula is fair or unfair?
- Can you suggest any way to make the loyalty point formula more robust?


## [Link](https://drive.google.com/file/d/1NjIfOJxarFbw9JxREmUJ8VTifSRVg2wV/view?usp=drive_link)




