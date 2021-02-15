# SQL Server Cheatsheet


    dd - this is day of month from 01-31
    dddd - this is the day spelled out
    MM - this is the month number from 01-12
    MMM - month name abbreviated
    MMMM - this is the month spelled out
    yy - this is the year with two digits
    yyyy - this is the year with four digits
    hh - this is the hour from 01-12
    HH - this is the hour from 00-23
    mm - this is the minute from 00-59
    ss - this is the second from 00-59
    tt - this shows either AM or PM
    d - this is day of month from 1-31 (if this is used on its own it will display the entire date)
    us - this shows the date using the US culture which is MM/DD/YYYY
    
    SELECT FORMAT (getdate(), 'dd-MM-yy') as date
    
