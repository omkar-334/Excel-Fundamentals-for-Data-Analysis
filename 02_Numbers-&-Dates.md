Numbers in excel automatically align to the right

Converting data
=value(text) - converts text to numeric data
=text(text, format) - returns dates or numerals as text
D- day
M- month
Y-year

Dates and date functions
=now() - returns current date and time
=today() - returns current date
=day(date) - returns day
=month(date) - returns month
=year(date) - returns year

Generating Valid dates
=date(year,month,day)
=month(1&B1)

Calculations with dates
=days(end_date, start_date) - returns difference of days
=workday(date, num_of_days) - returns date after working days
=workday.intl(start, days, [weekend],[holidays])  - how many days are weekend days
	Weekend codes - [0,1,0,0,0,0,1]
	Excel starts with monday, 1 for non working day, 0 for working day
=networkdays(start, end, [holidays]) - returns number of working days

Sophisticated date calculations
=eomonth(date, relativemonth) - retruns end of month
=edate(date, months) - adds or subtracts months to the date

=yearfrac( start, end) - caluculates % of year between 2 dates
=round(num, digits) - rounds off a number
=rounddown(num, digits) - rounds towards 0
=roundup(num, digits) - rounds away from 0
mround, even , odd, ceiling.math, floor.math
