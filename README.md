# module2_challenge

This analysis was performed for our friend Steve. The orginal analysis and vba script shows key performance indicators (volume, starting price and ending price) of a list of stocks. The original vba code was refactored to make this analysis more easily repeatable for Steve or anyone else who wants to analyse a list of stocks.


RESULTS:
Refactoring the script made the run time twice as fast. One reason for this is by removing nested loops we cut out many branched-logic options. There is only one loop with nested conditionals and that would seem to be a major factor in run time. 

<img width="236" alt="2017" src="https://user-images.githubusercontent.com/95047485/147706334-5ca92114-2680-4743-ab02-1ebc383694e6.PNG">

<img width="230" alt="2018" src="https://user-images.githubusercontent.com/95047485/147706340-958f764d-70ff-4405-a869-598cc2afea18.PNG">

SUMMARY:

Since the code has been refactored it makes the run time faster which will allow for futher stock analysis of much larger datasets. For the This code can now be more easily adapted ot larger datasets and the performance can be measured with the built-in timer.

