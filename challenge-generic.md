# currency-data
## the challenge
We are a company based in Munich, Germany and are expanding internationally to the US and Switzerland. 
We need to price our products in CHF and USD. Our pricing team needs a dashboard that show the current 
value of a EUR amount in CHF and USD. Also we would like to have an overview of the last two weeks 
conversion rates in a graphical chart.

## your tasks
You need to retrieve (current) currency rates (on a regular basis) for conversion from **EUR to USD** and **EUR to CHF** (**and vice versa**) from 
the https://currencylayer.com/ API and persist the data in a PostgreSQL DBMS (you'll have to sign up for a free account).

## requirements
1. Define an appropriate data model & table structure
2. Provide an application entry point, which loads currency data from the currencylayer API and persists it in your database
3. Make sure we have the most recent rates every morning at 8:00 CET
4. Create a simple frontend, which allows us to input currency values and convert them according to the selected currencies
5. Add a graphical representation of the recent (e.g. two weeks) daily rates for a selected source and destination currencies (feel free to use rates.json seed file)

## constraints
- Use a framework / stack you are familiar with, ideally a MVC based stack, like Django (python), Play (java), MVC.net, ...
- On the frontend side you are free to choose between old school HTML/JS or a modern JS framework
- Please use an open source currency layer library, if it is available for your chosen stack, e.g.
-- https://pypi.org/project/currencylayer/
-- https://github.com/keymusicman/CurrencyLayer4NET
-- https://github.com/helmethair-co/currency-layer-api

## discussion
- Entity / Schema design - what is the best way to persist the business objects here in a maintainable way?
- What is the best way to represent monetary data?
- What would you need to add if we were to put this implementation into production?
- What are the advantages / disadvantages of 3rd party libraries?
- How would you test this?

## hints
- Use any library you want
- Any feature from your chosen framework
- Any feature from PostgreSQL 11+
- Follow your and community best practices
