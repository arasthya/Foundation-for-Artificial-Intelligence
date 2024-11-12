# Foundation-for-Artificial-Intelligence
Team task at Startup Campus

# Case 1: I Want to Withdraw All My Savings in Cash!
As we know, in Indonesia there are several denominations of money as follows:
Paper Money:
Rp 100,000, Rp 50,000, Rp 20,000, Rp 10,000, Rp 5,000, Rp 2,000
Coins:
Rp 1,000, Rp 500, Rp 200, Rp 100

*To make it easier, we assume that all Rp. 1000 denominations are coins.

There are circumstances where the bank must liquidate all customer savings in the form of money, if the
customer requests it. And imagine this is happening right now in front of you, help the bank to calculate how many
denominations of money are needed.
Here is the rule:
1. Banks must prioritize the largest denominations first to be issued.
2. If there is a balance that cannot be cashed, the bank must inform it.
3. Bank must calculate how many number of Paper Money needed and Coins needed.
4. Banks can only disburse a maximum amount of 1 billion Rupiah.

Make a python code that receives an integer number of customer savings from 0 - 1 Billions.
Input:
> 2000000000

Output:
> Maximum Saving is 1000000000

Input:
> -100

Output:
> Please input the correct number

Input:
> 1245123
Output:
> Amount of currency Rp 100,000: 12
> Amount of currency Rp 50,000: 0
> Amount of currency Rp 20,000: 2
> Amount of currency Rp 10,000: 0
> Amount of currency Rp 5,000: 1
> Amount of currency Rp 2,000: 0
> Amount of currency Rp 1,000: 0
> Amount of currency Rp 500: 0
> Amount of currency Rp 200: 0
> Amount of currency Rp 100: 1
>
> Total Paper Money: 15
> Total Coins: 1
> Cannot be cashed out: 23
