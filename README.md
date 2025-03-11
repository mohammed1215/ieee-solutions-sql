# ieee-solutions-sql

### solution 1
select * from CITY where population > 100000 and countrycode = 'USA'

### solution 2
select name from Employee order by name

### solution 3
select tweet_id from Tweets where len(Tweets.content) > 15

### solution 4
update Salary set sex = 
case 
when sex = 'm' then 'f'
when sex = 'f' then 'm'
end
