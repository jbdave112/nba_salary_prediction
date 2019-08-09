## 2019 NBA Free Agency Analysis 

The summer of 2019 saw a huge overhaul of players. With so much money handed out, this offseason may be a good indicator of which teams are set up to succeed and which may struggle. To measure the prudence of these contracts I tested different regression models to create a market value for each free agent. 

Data was taken from the advanced stats and points per 100 possessions pages from basketball-reference.com for the 2017 and 2018 free agent class.

After testing lasso regression, ridge regression, random forest, as well as, various ensemble techniques, the voting regressor performed the best out of all tested models. The voting regressor model used a combination of basic linear regression, random forest, lasso regression, and ridge regression. 

The best values of free agency according to the model were high quality role players who signed team friendly contracts.

### Top 10 Values

| Player | Team | Projected Value | Contract Avg. | Net Value |
| :----: | :---: | :---: | :---: | :---: |
| Kevon Looney | Golden State Warriors | $15.0m | $5.0m | $10.0m |
| Wesley Matthews | Milwaukee Bucks | 11.7 | 2.6 | 9.0 |
| Emmanuel Mudiay | Utah Jazz | 10.5 | 1.7 | 8.8 |
| JaVale McGee | L.A. Lakers | 12.0 | 4.1 | 7.9 |
| Jeff Green | Utah Jazz | 10.5 | 2.6 | 7.9 |
| Derrick Rose | Detroit Pistons | 15.4 | 7.5 | 7.9 |
| Enes Kanter | Boston Celtics | 12.6 | 4.9 | 7.7 |
| Jeremy Lamb | Indiana Pacers | 17.7 | 10.5 | 7.2 |
| Reggie Bullock | New York Knicks | 11.3 | 4.1 | 7.2 |
| Robin Lopez | Milwaukee Bucks | 12.0 | 4.9 | 7.1 |

### Teams that found the best value

| Team | Net Value|
| :---: | :---: |
| L.A. Lakers | $25.3m |
| Utah Jazz | 20.4 |
| Boston Celtics | 14.9 |
| Chicago Bulls | 13.0 |
| Orlando Magic | 11.4 |

#### L.A. Lakers a Good Front Office?

The L.A. Lakers had a whirlwind of an offseason with most of their contracts expiring, and oh yeah, trading for Anthony Davis. The front office which has been criticized, and rightly so, for the team that was built around Lebron James last year appear to have learned from their mistakes.
They paired Lebron with another top 5 player, in AD, and surrounded the dynamic duo with shooting and value contracts like JaVale McGee.

#### Smooth Moves

Another team that many experts see as a contender are the Utah Jazz. The Jazz have drastically improved their offense with the additions of Mike Conley and Bojan Bogdanovic, and according to the model their signings of Emmanuel Mudiay and Jeff Green were great values. Can Utah's shrewd signings overcome their lack of star power?

#### Ainge at it Again

Despite losing Kyrie Irving and Al Horford, Danny Ainge was able to spend efficiently and should have the Celtics back near the top of the conference. The big addition for the Celts was the signing of Kemba Walker. There was a lot of discussion about whether he is worth a max. According to the model Kemba Walker was, indeed, worth the contract.
The biggest bargain for the Celtics, however, was Enes Kanter who received $7.7m less than the model predicted his market value to be.

#### Mid-Market Magic

The Chicago Bulls and Orlando Magic came in fourth and fifth respectively. Both signing players at a great value. The biggest two being Thaddeus Young for the Bulls and Nikola Vucevic for the Magic.

### Top 10 most overpaid 

| Player | Team | Projected Value | Contract Avg. | Net Value |
| :----: | :---: | :---: | :---: | :---: |
| Klay Thompson | Golden State Warriors | $22.2m | $38.0m | -$15.7m |
| Khris Middleton | Milwaukee Bucks | 20.5 | 35.5 | -15.0 |
| Tobias Harris | Philadelphia 76ers | 22.7 | 36.0 | -13.3 |
| Terry Rozier | Boston Celtics | 7.3 | 18.9 | -11.6 |
| Jonas Valanciunas | Memphis Grizzlies | 7.6 | 15.0 | -7.4 |
| Jimmy Butler | Philadelphia 76ers | 29.0 | 35.2 | -6.2 |
| Dewayne Dedmon | Sacramento Kings | 7.2 | 13.3 | -6.1 |
| Bobby Portis | New York Knicks | 9.3 | 15.4 | -6.0 |
| Kevin Durant | Brooklyn Nets | 35.5 | 41.1 | -5.6 |
| Marcus Morris | New York Knicks | 10.1 | 15.0 | -4.9 |

### Teams that found the least value

| Team | Net Value|
| :---: | :---: |
| Philadelphia 76ers | -$19.4m |
| Sacramento Kings | -12.6 |
| Charlotte Hornets | -11.6 |
| Memphis Grizzlies | -8.1 |
| Miami Heat | -6.2 |

#### Tier 3 stars
The highest overpays according to the model were lower Tier star players, like Klay Thompson, Khris Middleton, and Tobias Harris, who were given max contracts. 

#### The Bounce

Jimmy Butter and Tobias Harris, bounced by Kawhi Leonard and the Raptors, both received max contracts. Harris stayed with the Sixers while Butler joined the Heat. Both contracts were judged as negative values by the model.


#### Big Men, Big Contracts
Memphis and Sacramento signed big men in Dewayne Dedmon and Jonas Valanciunas to lucrative contracts that the model deemed to be overpays.


#### Rozier-Colored Glasses
And then for whatever reason Michael Jordan and the Charlotte Hornets thought it was a good idea to give Terry Rozier a contract worth 57 million dollars.

