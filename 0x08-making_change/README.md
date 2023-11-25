-------------CODE IMPLEMENTATION ---------------

You initialize the dp array with the first element as 0 and the rest as infinity (float("inf")).

You iterate through each coin value and update the dp array accordingly to find the minimum number of coins needed for each possible total.

Finally, you return dp[-1] (last element of the dp array), which represents the minimum number of coins needed to meet the total. If it's still infinity, you return -1 to indicate that the total cannot be achieved with the given coins.
