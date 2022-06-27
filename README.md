# Stock Analysis
The purpose of this analysis is to provide the user with condensed version of thousands of rows of stock data. It compiles total daily volume and yearly return for each stock in a specific year. The original macro was written to analyze years 2017 and 2017. This macro has been reformatted so that it’s adaptable to any year other year of data the user would like analyzed. It also has a quicker run time. 


## Results 

### 2017 
The year 2017 was a good year. Most stock returns were in the positives except for one, TERP, which had a return of -7.2. The stocks that did best were DQ (199.4%) and SEDG (184.5%). 

Execution time pre and post refactoring is 0.3125 and 0.296875 respectively.

![Origional Execution2017](https://user-images.githubusercontent.com/107375554/175858623-9bfda650-f2ef-4d11-b54d-f0ff2cf99917.png)
![VBA_Challenge_2017](https://user-images.githubusercontent.com/107375554/175858647-bb6595fa-0c9f-4db4-8bfd-9302a9cec301.png)





### 2018
The year 2018, on the other hand, was rather bad. Only two stocks returned in the positives: ENPH (82.9%) and RUN (84.0%). Our former front runner, DQ, had a -62.6% return and SEDG returned at -7.8%. 

Execution time pre and post refactoring is 0.3242188 and 0.2890625 respectively.
![Origional Execution 2018](https://user-images.githubusercontent.com/107375554/175858742-909d361e-5345-49e4-a572-05d447a7508a.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/107375554/175858752-f45d3346-c4c8-4cf1-a7af-5c642e131e08.png)




## Summary
There are advantages to refactoring code. It makes it more flexible to use with other data sets and agile for larger data sets. A disadvantage of refactoring code is that is it needs to be very well commented because if you try to go back and use it in the future, you need to be able to clearly decipher what each line, loop, and variable is doing. 

My original VBA script was commented but not as much as I would like it to have been. When trying to refactor I felt the pain of their absence because I had to figure out all over again what each loop was supposed to be doing. However, once I got it working, I was grateful for the few comments I did originally have; and it was satisfying to see that the new code was running quicker. 

