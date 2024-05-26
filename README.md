Reference course link: https://www.youtube.com/watch?v=xfzGZB4HhEE
# Algorithmic Trading
Algorithmic trading is the use of algorithms utilised by computers to make investment decisions. The main difference in different trading algorithms is speed of execution.

## Programming languages used
Due to the simplicity, compactness of its codes and availability of a vast range of libraries, Python is the most popular language in the development and implementation of trading algorithms.

However, due to the slower speed of Python code, we often use Python codes as triggers for codes written in other faster languages. This is seen in the use of Numpy, which is a Python library but is implemented using C (a much faster language than Python).

## General steps in algorithmic trading
1. Collect data
2. Develop a hypothesis (on which the investment strategy will be based)
3. Test the strategy on past data that ranges across time periods and locations
   (backtesting)
4. Implement the strategy for real

For example, imagine the following. You collected data on a large number of firms, with records containing various business measures for each firm.

After performing statistical tests to determine the significant factors for one or business measures that you care about, you hypothesise that the liquidity of a company (measured by the working capital ratio i.e. ratio between current assets and current liabilities) is a major factor in determining the value of a company, and predicts future increases in share values.

You then develop a strategy based on this hypothesis (which could be as simple as looking for the company with the highest liquidity, or more complex, such as an algorithm that may also consider other factors), and test it on historical data, preferably across multiple regions in the world.

If the strategy sufficiently accurate in determining high value companies, you implement this strategy in an algorithm and eventually a code.

# Value investment
Value investment means investing in stocks (i.e. company shares) that are cheap relative to their value (which is evaluated using measures of business value such as earnings and assets).

In other words, value investment is the investment on the stocks that are priced lower than their intrinsic value (i.e. the company is underselling its stocks).

## Multiples
Algorithmic value investment relies on the concept of multiples. Multiples are values calculated by dividing a company's stock price to some measure of the company's business value, such as earnings or assets. Some common multiples used are:
- Price-to-earnings
- Price-to-book-value
- Price-to-free-cash-flow
____
NOTE:
Price means stock price, and all the measures here are annual estimates (annual estimate of earnings etc.).

### Minimsing disadvantes of different types of multiples (composite)
Each type of multiple has its advantages and disadvantages. One way to minimise the disadvantages of a multiple is to use a composite, which is an everage of multiple different valuation strategies.
