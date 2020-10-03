# Finance_Website_Cs50
Implementing a website via which users can “buy” and “sell” stocks.

![Image for finance](https://cs50.harvard.edu/x/2020/tracks/web/finance/finance.png)

C$50 Finance, a web app via which you can manage portfolios of stocks. Not only will this tool allow you to check real stocks’ actual prices and portfolios’ values, it will also let you buy (okay, “buy”) and sell (okay, “sell”) stocks by querying IEX for stocks’ prices.
Using IEX API key using URL like https://cloud-sse.iexapis.com/stable/stock/nflx/quote?token=API_KEY

- Visit iexcloud.io/cloud-login#/register/.
- Enter your email address and a password, and click “Create account”.
- On the next page, scroll down to choose the Start (free) plan.
- Once you’ve confirmed your account via a confirmation email, sign in to iexcloud.io.
- Click API Tokens.
- Copy the key that appears under the Token column

$ export API_KEY=value
Start Flask’s built-in web server (within finance/):

Using this command start the server.

$ flask run
