# Currency Data
## The task
You need to fetch current currency rates for EUR to USD and EUR to CHF from the currencylayer API and store them into a PostgreSQL database table.
https://currencylayer.com (you'll have to sign up for a free account)
​
## Goals
- Define the table structure
- Provide a Ruby script that fetches the data and stores it in the table
- Build a simple Website, which allows to input currency values and translate them accordingly.
​
## Constraints
- Use `money-currencylayer-bank` gem
​
## Hints
- Use any gem or lib you want
- Any future from Ruby 2.x
- Any future from PostgreSQL
​
## Discussion
| Task component | Possible questions |
|--|--|
| Add `money-currencylayer-bank` gem via bundler | What is bundler ? |
|  | What is Gemfile ? |
|  | Should Gemfile.lock be committed or not ? |
| Use the Gem to fetch current currency rates for EUR->USD and EUR->CHF  | |
| Define a PSQL table to store the rates | How do you set the PK and why ? |
| | Currencies as string, Enum or create an String -> ID mapping ? | 
| | When using Enum, what are the advantages and disadvantages of each type? |
| | What PSQL data type do you use for money? Float or Decimal? Why? |
| Store rates into this table | what Gem to use ? |
| | SQL injection ?! |
