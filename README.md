# SQL Server Cheatsheet

## Date formatting

    dd - day of month from 01-31
    dddd - day long version
    MM - month number
    MMM - month name short
    MMMM - month name long
    yy - year
    yyyy - year 4
    hh - hour
    HH - 24 hour format hour
    mm - minute
    ss - second
    tt - AM/PM
    d - day of month
    
    SELECT FORMAT (getdate(), 'MM-dd-yyyy') as date
    
## Number formatting
    Select Format(12345.67,'#,##0.00')  

