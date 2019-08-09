The summer of 2019 saw the biggest overhaul of players in a single offseason in the history of the NBA and perhaps all of sports. With so much cash handed out, this offseason may be a sign of which teams are going to succeed and which aren't. In an attempt to measure how prudent each of these contract were I tested different regression models to create a market value for each free agent. 
Data was taken from the advanced stats and points per 100 possesions pages from basketball-reference.com from the 2017 and 2018 free agent class. The target value I was attempting to predict was the yearly average salary.
After testing lasso, ridge, random forest, as well as, ensemble techniques, the average regressor performed the best out of all tested models. The average regressor model used a combination of basic linear regression, random forest, lasso, and ridge. Here are the results.


The highest overpays according to the model were B Tier Players who were given max contracts. These players were Klay Thompson, Khris Middleton, and Tobias Harris. Following These Players was the baffling contract given to Terry Rozier by the GOAT, Michael Jordan, owner of the Charlotte Hornets.

| Player | Team | Projected Value | Contract Avg. | Net Value |
| :----: | :---: | :---: | :---: | :---: |
| Klay Thompson: | Golden State | $22.2m | $37.98m | $15.7m
| Khris Middleton | Milwaukee| 20.5 | 35.5 | 15.0
| Tobias Harris | Philadelphia | 22.7 | 36.0 | 13.3
| Terry Rozier | Boston | 7.3 | 18.9 | 11.6
| Jonas Valanciunas | Memphis | 7.6 | 15.0 | 7.4
| Jimmy Butler | Philadelphia | 29.0 | 35.175 | 6.2
| Dewayne Dedmon | Sacramento | 7.2 | 13.33 | 6.1
| Bobby Portis | New York | 9.3 | 15.375 | 6.0
| Kevin Durant | New Jersey | 35.5 | 41.1 | 5.6
| Marcus Morris | New York | 10.1 | 15.0 | 4.9
