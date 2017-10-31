# Browns Kicker Analysis (2015)

This is an analysis I put together for the Cleveland Browns on their kicking game following the 2015 season.

I was asked to consider two questions in my analysis:
1) How did the kickers for the Browns perform in 2015, relative to what an NFL team should expect from the position?
2) Given the kickers on our roster (in 2015), how should we expect them to perform in 2016? How does that compare to the rest of the league?

The method of analysis, tools, etc were left completely for me to decide. 

I choose to develop my own metric for field goal accuracy, adjusted field goal percentage, to measure historical kicker performances. I then used bayesian updating and the beta distribution, which works well with binary outcomes like make-miss, to forecast future kicker performances.

You can view the [project code in an R Notebook](https://github.com/colekev/brown_kicker_analysis/blob/master/browns_kicker_analysis.Rmd), or download the HTML file for viewing the code and visualizations in your brower.
