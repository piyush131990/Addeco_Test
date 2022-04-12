# Addeco_Test
Create a .NET (Framework, not Core) webservice which accepts a string and returns a string. It should:
expect to receive a string which is a day of the week (Monday, Tuesday etc). 
return the date which is the next day of that name, based on the current UTC date/time. 
never return the current day, even if it matches.
 For example:
given “Monday” and called at midnight on 25 June, it should return 29 June 2021 as a string, in whatever format you choose
given “Thursday” and called at midnight on 25 June, it should return 2 July 2021 as a string, in whatever format you choose
