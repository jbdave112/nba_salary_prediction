The summer of 2019 saw a huge overhaul of players. With so much money handed out, this offseason may be a good indicator of which teams are set up to succeed and which aren't. To measure the prudence of these contracts I tested different regression models to create a market value for each free agent. 

Data was taken from the advanced stats and points per 100 possessions pages from basketball-reference.com for the 2017 and 2018 free agent class.

After testing lasso, ridge, random forest, as well as, various ensemble techniques, the voting regressor performed the best out of all tested models. The voting regressor model used a combination of basic linear regression, random forest, lasso, and ridge. 

The best values of free agency according to the model were high quality role players who signed team friendly contracts.

### Top 10 Values

| Player | Team | Projected Value | Contract Avg. | Net Value |
| :----: | :---: | :---: | :---: | :---: |
| Kevon Looney | Golden State | $15.0m | $5.0m | $10.0m |
| Wesley Matthews | Milwaukee | 11.7 | 2.6 | 9.0 |
| Emmanuel Mudiay | Utah | 10.5 | 1.7 | 8.8 |
| JaVale McGee | L.A. Lakers | 12.0 | 4.1 | 7.9 |
| Jeff Green | Utah | 10.5 | 2.6 | 7.9 |
| Derrick Rose | Detroit | 15.4 | 7.5 | 7.9 |
| Enes Kanter | Boston | 12.6 | 4.9 | 7.7 |
| Jeremy Lamb | Charlotte | 17.7 | 10.5 | 7.2 |
| Reggie Bullock | New York | 11.3 | 4.1 | 7.2 |
| Robin Lopez | Milwaukee | 12.0 | 4.9 | 7.1 |

### Teams that found the best value

| Team | Net Value|
| :---: | :---: |
| L.A. Lakers | $25.3m |
| Utah | 20.4 |
| Boston | 14.9 |
| Chicago | 13.0 |
| Orlando | 11.4 |

The L.A. Lakers had a whirlwind of an offseason with most of their contracts expiring, and oh yeah, trading for Anthony Davis. The front office which has been criticized, and rightly so, for the team that was built around Lebron James which lead to him missing the playoffs for the first time in 14 years, seem to have learned from their mistakes.
They paired Lebron with another top 5 player, in AD, and surrounded the dynamic duo with shooting and value contracts like JaVale McGee.

Another team that many experts see as a contender are the Utah Jazz. The Jazz have drastically improved their offense with the additions of Mike Conley and Bojan Bogdanovic, and according to the model their signings of Emmanuel Mudiay and Jeff Green were great values. Can Utah's shrewd signings overcome their lack of star power?

Coming in third are the Boston Celtics. The big addition for the Celts was the signing of Kemba Walker. There was a lot of discussion about whether he is worth a max. According to the model Kemba Walker was, indeed, worth the contract.
The biggest bargain for the Celtics, however, was Enes Kanter who received $7.7m less than the model predicted his market value to be.

The Chicago Bulls and Orlando Magic came in fourth and fifth respectively. Both signing players at a great value. The biggest two being Thaddeus Young and Nikola Vucevic.

The highest overpays according to the model were B Tier star players who were given max contracts. 

### Top 10 most overpaid 

| Player | Team | Projected Value | Contract Avg. | Net Value |
| :----: | :---: | :---: | :---: | :---: |
| Klay Thompson | Golden State | $22.2m | $37.98m | -$15.7m |
| Khris Middleton | Milwaukee | 20.5 | 35.5 | -15.0 |
| Tobias Harris | Philadelphia | 22.7 | 36.0 | -13.3 |
| Terry Rozier | Boston | 7.3 | 18.9 | -11.6 |
| Jonas Valanciunas | Memphis | 7.6 | 15.0 | -7.4 |
| Jimmy Butler | Philadelphia | 29.0 | 35.175 | -6.2 |
| Dewayne Dedmon | Sacramento | 7.2 | 13.33 | -6.1 |
| Bobby Portis | New York | 9.3 | 15.375 | -6.0 |
| Kevin Durant | New Jersey | 35.5 | 41.1 | -5.6 |
| Marcus Morris | New York | 10.1 | 15.0 | -4.9 |

### Teams that found the least value

| Team | Net Value|
| :---: | :---: |
| Philadelphia | -$19.4m |
| Sacramento | -12.6 |
| Charlotte | -11.6 |
| Memphis | -8.1 |
| Miami | -6.2 |

Jimmy Butter and Tobias Harris, bounced by Kawhi Leonard and the Raptors, both received max contracts. Harris stayed with the Sixers while Butler joined the Heat. Both contracts were judged as negative values by the model.

Memphis and Sacramento signed big men in Dewayne Dedmon and Jonas Valanciunas to lucrative contracts that the model deemed to be overpays.

And then for whatever reason Michael Jordan and the Charlotte Hornets thought it was a good idea to give Terry Rozier a contract worth 57 million dollars.

