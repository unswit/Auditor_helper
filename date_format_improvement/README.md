# date_format_improvement  
Chinese vision: https://blog.csdn.net/DannieZ/article/details/106387096  
My roommate want to find the foreign exchange rate in every client's trade day by "Vlookup".  
She also have another table contains "foreign exchange rates" in everyday except weekends.  
(During the weekends, the rates are typically stable as the major markets are closed and   
there is very little trading to be reported.)  

So she has two date, one is from clients and anotherone is from "foreign exchange rates" table.  
The date format in clients data is : mm/dd/yy which is excel can't recognize it as a "date"  
The date format in "foreign exchange rates" table is: dd/mm/yy which is standard date format.  

I should change the "mm/dd/yy" to "dd/mm/yy".


