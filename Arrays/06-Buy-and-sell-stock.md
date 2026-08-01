# Best Time to Buy and Sell Stock

## Pattern
Linear Traversal + Running Minimum

## Recognition
If the question asks:
- Buy before Sell
- Maximum Profit
- One Transaction

Think of maintaining the minimum price seen so far.

## Optimal Approach
1. Initialize:
   - minPrice = first day's price
   - maxProfit = 0
2. Traverse the array once.
3. Update minPrice if a smaller price is found.
4. Calculate:
   profit = currentPrice - minPrice
5. Update maxProfit.
6. Return maxProfit.

## Time Complexity
O(n)

## Space Complexity
O(1)

## Interview Tips
- Don't think "Maximum Price - Minimum Price".
- The buying day must always come before the selling day.
- Keep track of the minimum price while traversing.
- Update profit at every step.

## Common Mistakes
- Finding global minimum and maximum.
- Buying after selling.
- Updating profit before updating minimum price.

## Similar Questions
- Best Time to Buy and Sell Stock II
- Best Time to Buy and Sell Stock III
- Best Time to Buy and Sell Stock with Cooldown
- Maximum Difference Between Two Elements

## Revision Trick
Buy → Minimum Price → Sell → Maximum Profit

## One-Line Summary
Maintain the minimum price seen so far and calculate the maximum possible profit at every step.
