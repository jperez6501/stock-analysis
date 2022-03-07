# stock-analysis
## Overview of Project 
### The purpose of this reformatted stock analysis is to utilize tickers to create a more time efficient macro. 

### Results
#### When the code ran the first time before it was refactored, it was running through several loops. Consequently, it was running on an average time of 0.38 seconds (top image). However, when the code was refactored to only loop through the entire data once, the running time was between 0.07-0.08 second (bottom image). The refactored code took about one fifth of the time then the original code.
<img width="418" alt="Stock Analysis with original macro" src="https://user-images.githubusercontent.com/100246124/157057861-708171f3-5367-4d6e-b90f-2754a634c124.png">
<img width="265" alt="Screen Shot 2022-03-07 at 10 00 06 AM" src="https://user-images.githubusercontent.com/100246124/157059401-e3dccf92-df84-4c0c-89b6-f746f25838c5.png">

####  As seen in the image below,first we create a ticker index and define it as in integer. We are creating three output arrays to hold 12 tickers (12). When creating the loop we initiative the ticker volume to zero and loop over all the rows. We increase the ticker volume by using the ticker index, tickerVolumes(tickerindex). Next we check that the first row is correctly selected and the last row is correctly assigned. 
<img width="647" alt="Screen Shot 2022-03-07 at 9 00 29 AM" src="https://user-images.githubusercontent.com/100246124/157059732-f9eec870-e8dd-49ae-9dc0-ce95eec7529e.png">


#### Lastly, we use a for loop to loop through the arrays. Notice that in this reformatted code, we are using tickers, tickerVolumes, tickerEndingPrices and tickerStartingPrices. Since our values remained the same, we know that we successfully refactored our code to use the tickerindex and since it took less time, we effectively refactored the code to run in less time, we effectively refactored the code to run in less time.
<img width="588" alt="Screen Shot 2022-03-07 at 9 21 24 AM" src="https://user-images.githubusercontent.com/100246124/157059817-d67cf91e-0fd3-4066-9f1f-2f7f5c703a54.png">


## Summary 
#### The advantages of refactoring the code is that we are only using a for loop instead of a nested for loop, this cuts down the time it takes to run the code. With a nested loop, we have to be careful to close the inner loop before we close the outer loop or our code will not run effectively, we have eliminated this problem with the refactored code. Another advantage of refactoring the code is that we are not using multiple variables and having the remember what variable to use when. We are creating a more efficient code by using the ticker index and eliminating the use for multiple variables. If you are ever running a code for a much larger data set, the time difference will be more significant and the refactored code will become more useful. 

#### The disadvantages with refactoring the code are that we are creating a wordier code, this leads to more room for error. An example would be that for my code, if I was not careful with writing the exact word each time (ticker vs tickers) it would produce multiple errors. Overall this refactored code is longer and while it does run faster, by a third of a second,  the time difference might not be worth rewriting a code where there is the potential for many more code errors. 
