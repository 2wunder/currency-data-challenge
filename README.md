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
5. When selecting rates, show a graph with the daily rates of the last weeks (add appropriate seed data to make it work)
6. 
​
## Constraints
- Use `money-currencylayer-bank` gem
​
## Hints
- Use any gem or lib you want
- Any feature from Ruby 2.x
- Any feature from PostgreSQL
​
## Discussion
| Task component | Possible questions |
|--|--|
| Add `money-currencylayer-bank` gem via bundler | What is bundler ? |
|  | What is Gemfile ? |
|  | Should Gemfile.lock be committed or not ? |
| Use the Gem to fetch current currency rates for EUR->USD, USD->EUR ,CHF->EUR and EUR->CHF  | |
| Define a PSQL table to store the rates |
| | Currencies as string, Enum or create an String -> ID mapping ? | 
| | When using Enum, what are the advantages and disadvantages of each type? |
| | What PSQL data type do you use for money? Float or Decimal? Why? |
| Storing rates | what Gem to use ? |
| | SQL injection ?! |
| | SQL injection ?! |
