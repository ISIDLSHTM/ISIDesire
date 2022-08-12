# ISIDesire
A short proof-of-concept that enables parameterisation and use of desirability functions.

To use, clone this repo and run run main.py, this will guide you through setup for a desirability function.

I suggest copy and pasting your generated quick setup save_string that will be printed for future use to a text file. An example desirability function save_string is included in save_strings.txt.



The example reflects an employer of a large company that sells a high value object that is attempting to determine there most and least effective senior salespeople.

The employer values those that can make a large number of sales, expecting greater than 10 per year and believing the average employer should make 20 sales. They do not believe that move that 100 sales a year are possible.

The employer values those that use minimal sick days, expecting less than 28 sick days per year and believing the average employer should take on average 5. Taking 3 or less sick days is conisdered optimal. 

The employer values those that manage juniors, prefering there seniors to manage 5 juniors each. The employer believes that those managing no juniors are undesirable. Similarly, managing 15 or more juniors is undesirable as the employer believes that the senior would be inable to provide adequate attention to each. Between 2 and 7 would be preffered.

To generate this from running main.py I typed:

N

b

Yearly_Sales

10

100

20

Yearly_sick_days

3

28

5

Juniors

0

5

15

2

7

end

15

12

end

