# VBA Stock Analysis

## Overview of Project
The purpose of this project was to assist a couple interested in investing in stock. They wanted to know which stocks were wrth investing in, so we created an analysis of stocks ranging from 2017 to 2018 to aid them in their decision making. Originally we created a macro that completed a similar task; however, we decdided to refactor it with hopes that this new macro would run more effificently.
### Results
2017 saw a lot more success than 2018 with regard to the return on stocks. The volume of trading from each stock varied year to year, but overall signfiicantly more stocks saw returns in 2017 than they did in 2018. The stocks with tickers "ENPH" and "RUN" saw returns in both 2017 and 2018, so those two would be worth a look. Our refactored macro really did increase the efficiency of the process as well. In both 2017 and 2018, the refactored code was able to process the information and provide output in about 0.6 seconds less time than it took with the original code. 

![VBA_Challenge_2017](https://user-images.githubusercontent.com/99751636/158441472-a3210ffe-d943-4071-93ca-c03f4c520c97.png)
![2017_RunTime_Original](https://user-images.githubusercontent.com/99751636/158442209-89a20eae-c36c-40cc-8666-edc0bdbe8059.png)
![VBA_Challenge_2017_Results](https://user-images.githubusercontent.com/99751636/158442241-9a30f40d-6bd9-45a3-a6e4-10b7dd326dbb.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/99751636/158442258-325e89b6-1125-4e8c-9a3a-03e80fc0d701.png)
![2018_RunTime Original](https://user-images.githubusercontent.com/99751636/158442276-1fb3d285-490d-43fb-8064-c8c4b8d5e6d1.png)
![VBA_Challenge_2018_results](https://user-images.githubusercontent.com/99751636/158442299-d09445b6-e37a-45fe-ae8f-2dfef2e92de0.png)
### Summary
It would appear as though refactoring the macro had a few advantages. Namely, the refactored code accomplished the same task as the original code, only with fewer steps. Thus, the run time was a lot faster and the code was a lot cleaner. I feel for the most part refactoring could have a positive impact, but I could see roadblocks arising when codes grow in size and complexity. It's easy to refactor code in an example like this one, where there is a small amount of code executing basic functions. If we had more code present that had more complex functions, however, it could present more opportunities to make an errors that lead to the whole macro being ineffective. 
