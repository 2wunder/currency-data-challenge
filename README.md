# Currency Data
## The task
You need to fetch current currency rates for EUR and USD and EUR and CHF (both ways) from the currencylayer API and store them into a PostgreSQL database table.
https://currencylayer.com (you'll have to sign up for a free account)
​
## Goals
1. Define an appropriate table structure
2. Provide a Ruby script that fetches the data and stores it in the table
3. Build a simple Website, which allows us to input currency values and translate them accordingly
4. Make sure we have the most recent rates every morning at 8:00 CET
5. When selecting rates, show a graph with the daily rates of the last weeks (feel free to use rates.json seed file)
​
## Constraints
- Use `money-currencylayer-bank` gem
​
## Hints
- Use any gem or lib you want
- Any feature from Ruby 2.x
- Any feature from PostgreSQL
​
