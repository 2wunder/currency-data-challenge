# Currency Data
## The task
You need to fetch current currency rates for conversion from EUR to USD and EUR to CHF (both ways) from the currencylayer API and store them into a PostgreSQL database table.
https://currencylayer.com (you'll have to sign up for a free account)
​
## Goals
1. Define an appropriate table structure
2. Provide a Ruby application that loads the data from the currencylayer API and stores it in the table
3. Build a simple frontend, which allows us to input currency values and convert them accordingly
4. Make sure we have the most recent rates every morning at 8:00 CET
5. Nice to have: On the frontend side, add a graph with the daily rates of the last weeks for a selected (dropdown) currenty (feel free to use rates.json seed file)
​
## Constraints
- Please use the `money-currencylayer-bank` gem

## Considerations
- Entity / Schema design - what is the best way to persist the data collected here in a maintainable way?
​- What is the best way to represent monetary data?
- What would you need to add if we were to put this implementation into production?
- What are the advantages / disadvantages of 3rd party libraries?
- How would you test this?

## Hints
- Use any gem or lib you want
- Any feature from current ruby versions
- Any feature from current PostgreSQL versions
- Follow your and community best practices
​
