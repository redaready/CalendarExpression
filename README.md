CalendarExpression
==================

CalendarExpression

date: YYYY.MM.DD

weekdays: [1-7]{1,7}

periode: /begin:date-end:date/

weekdays_in_periode: periode weekdays

calendar: date|periode|weekdays_in_periode


operators:

union: +

difference: -

calendar expression: calendar [operator calendar]...

exemple:

/2012.01.01-2013.01.01/1357+/2012.12.31-2013.04.01/+2013.05.01-2013.01.01

