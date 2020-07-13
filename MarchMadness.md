March Madness
================

For this assignemnt I chose to analyze the March Madnesss dataset. I
must admit that I’m not a follower of basketball, not even during March
Madness. In fact, last year was my first time making a bracket for the
tournament and I only made it because I was peer pressured by my
coworkers. I showcased how little I knew by picking the top seeds for
every single matchup– neeless to say I didn’t do very well. That being
said, I’m not sure where to begin with this overwhelmingly large
dataset, but I’ll give it my best effort.

### Win/Loss Ratio: 2015-2019 Regular Season

I know that wins are a good thing in sports, and losing is not so good.
Let’s start off with an overview of which teams have had a high Win:Loss
ratio over the last 5 seasons. The exact numer of seasons is arbitrary,
but I think recent years would be a better predictor of future
performance compared to older years, so I chose the last 5. Here’s a
table of the top 100 W/L ratios over the last 5 seasons:

<div data-pagedtable="false">

<script data-pagedtable-source type="application/json">
{"columns":[{"label":["name"],"name":[1],"type":["fctr"],"align":["left"]},{"label":["season"],"name":[2],"type":["int"],"align":["right"]},{"label":["wins"],"name":[3],"type":["int"],"align":["right"]},{"label":["losses"],"name":[4],"type":["int"],"align":["right"]},{"label":["WL_ratio"],"name":[5],"type":["dbl"],"align":["right"]}],"data":[{"1":"Gonzaga","2":"2017","3":"32","4":"1","5":"32.000000"},{"1":"Villanova","2":"2015","3":"32","4":"2","5":"16.000000"},{"1":"Gonzaga","2":"2015","3":"31","4":"2","5":"15.500000"},{"1":"Virginia","2":"2018","3":"31","4":"2","5":"15.500000"},{"1":"Arizona","2":"2015","3":"31","4":"3","5":"10.333333"},{"1":"Houston","2":"2019","3":"31","4":"3","5":"10.333333"},{"1":"Villanova","2":"2017","3":"31","4":"3","5":"10.333333"},{"1":"Wisconsin","2":"2015","3":"31","4":"3","5":"10.333333"},{"1":"Buffalo","2":"2019","3":"30","4":"3","5":"10.000000"},{"1":"Gonzaga","2":"2019","3":"30","4":"3","5":"10.000000"},{"1":"Northern Iowa","2":"2015","3":"30","4":"3","5":"10.000000"},{"1":"Virginia","2":"2015","3":"29","4":"3","5":"9.666667"},{"1":"Virginia","2":"2019","3":"29","4":"3","5":"9.666667"},{"1":"Arizona","2":"2017","3":"30","4":"4","5":"7.500000"},{"1":"Cincinnati","2":"2018","3":"30","4":"4","5":"7.500000"},{"1":"Gonzaga","2":"2018","3":"30","4":"4","5":"7.500000"},{"1":"SMU","2":"2017","3":"30","4":"4","5":"7.500000"},{"1":"Villanova","2":"2018","3":"30","4":"4","5":"7.500000"},{"1":"Duke","2":"2015","3":"29","4":"4","5":"7.250000"},{"1":"Kansas","2":"2016","3":"29","4":"4","5":"7.250000"},{"1":"Michigan St","2":"2018","3":"29","4":"4","5":"7.250000"},{"1":"MTSU","2":"2017","3":"29","4":"4","5":"7.250000"},{"1":"Nevada","2":"2019","3":"29","4":"4","5":"7.250000"},{"1":"UCLA","2":"2017","3":"29","4":"4","5":"7.250000"},{"1":"Wichita St","2":"2017","3":"29","4":"4","5":"7.250000"},{"1":"Kansas","2":"2017","3":"28","4":"4","5":"7.000000"},{"1":"New Mexico St","2":"2019","3":"28","4":"4","5":"7.000000"},{"1":"St Mary's CA","2":"2017","3":"28","4":"4","5":"7.000000"},{"1":"Ark Little Rock","2":"2016","3":"27","4":"4","5":"6.750000"},{"1":"Wichita St","2":"2015","3":"27","4":"4","5":"6.750000"},{"1":"SF Austin","2":"2015","3":"26","4":"4","5":"6.500000"},{"1":"Wofford","2":"2019","3":"26","4":"4","5":"6.500000"},{"1":"Murray St","2":"2019","3":"25","4":"4","5":"6.250000"},{"1":"Cincinnati","2":"2017","3":"29","4":"5","5":"5.800000"},{"1":"Duke","2":"2019","3":"29","4":"5","5":"5.800000"},{"1":"Kentucky","2":"2017","3":"29","4":"5","5":"5.800000"},{"1":"Michigan St","2":"2016","3":"29","4":"5","5":"5.800000"},{"1":"Notre Dame","2":"2015","3":"29","4":"5","5":"5.800000"},{"1":"UC Irvine","2":"2019","3":"29","4":"5","5":"5.800000"},{"1":"Villanova","2":"2016","3":"29","4":"5","5":"5.800000"},{"1":"Oregon","2":"2017","3":"28","4":"5","5":"5.600000"},{"1":"St Mary's CA","2":"2018","3":"28","4":"5","5":"5.600000"},{"1":"Tennessee","2":"2019","3":"28","4":"5","5":"5.600000"},{"1":"Vermont","2":"2017","3":"28","4":"5","5":"5.600000"},{"1":"Xavier","2":"2018","3":"28","4":"5","5":"5.600000"},{"1":"Chattanooga","2":"2016","3":"27","4":"5","5":"5.400000"},{"1":"Loyola-Chicago","2":"2018","3":"27","4":"5","5":"5.400000"},{"1":"UNC Wilmington","2":"2017","3":"27","4":"5","5":"5.400000"},{"1":"Xavier","2":"2016","3":"27","4":"5","5":"5.400000"},{"1":"St Mary's CA","2":"2016","3":"26","4":"5","5":"5.200000"},{"1":"Belmont","2":"2019","3":"25","4":"5","5":"5.000000"},{"1":"Hawaii","2":"2016","3":"25","4":"5","5":"5.000000"},{"1":"Murray St","2":"2015","3":"25","4":"5","5":"5.000000"},{"1":"New Mexico St","2":"2017","3":"25","4":"5","5":"5.000000"},{"1":"New Mexico St","2":"2018","3":"25","4":"5","5":"5.000000"},{"1":"SMU","2":"2016","3":"25","4":"5","5":"5.000000"},{"1":"Valparaiso","2":"2015","3":"25","4":"5","5":"5.000000"},{"1":"Murray St","2":"2018","3":"24","4":"5","5":"4.800000"},{"1":"Cincinnati","2":"2019","3":"28","4":"6","5":"4.666667"},{"1":"Michigan","2":"2019","3":"28","4":"6","5":"4.666667"},{"1":"Michigan St","2":"2019","3":"28","4":"6","5":"4.666667"},{"1":"Nevada","2":"2017","3":"28","4":"6","5":"4.666667"},{"1":"North Carolina","2":"2016","3":"28","4":"6","5":"4.666667"},{"1":"Purdue","2":"2018","3":"28","4":"6","5":"4.666667"},{"1":"SF Austin","2":"2016","3":"23","4":"5","5":"4.600000"},{"1":"Kentucky","2":"2019","3":"27","4":"6","5":"4.500000"},{"1":"Maryland","2":"2015","3":"27","4":"6","5":"4.500000"},{"1":"Monmouth NJ","2":"2017","3":"27","4":"6","5":"4.500000"},{"1":"North Carolina","2":"2019","3":"27","4":"6","5":"4.500000"},{"1":"Oregon","2":"2016","3":"27","4":"6","5":"4.500000"},{"1":"Utah St","2":"2019","3":"27","4":"6","5":"4.500000"},{"1":"Colorado St","2":"2015","3":"26","4":"6","5":"4.333333"},{"1":"Illinois St","2":"2017","3":"26","4":"6","5":"4.333333"},{"1":"LSU","2":"2019","3":"26","4":"6","5":"4.333333"},{"1":"SMU","2":"2015","3":"26","4":"6","5":"4.333333"},{"1":"Texas Tech","2":"2019","3":"26","4":"6","5":"4.333333"},{"1":"UNC Greensboro","2":"2019","3":"26","4":"6","5":"4.333333"},{"1":"Vermont","2":"2019","3":"26","4":"6","5":"4.333333"},{"1":"Wofford","2":"2015","3":"26","4":"6","5":"4.333333"},{"1":"Liberty","2":"2019","3":"25","4":"6","5":"4.166667"},{"1":"Louisiana","2":"2018","3":"25","4":"6","5":"4.166667"},{"1":"UAB","2":"2016","3":"25","4":"6","5":"4.166667"},{"1":"S Dakota St","2":"2018","3":"24","4":"6","5":"4.000000"},{"1":"SF Austin","2":"2018","3":"24","4":"6","5":"4.000000"},{"1":"Stony Brook","2":"2016","3":"24","4":"6","5":"4.000000"},{"1":"Valparaiso","2":"2016","3":"24","4":"6","5":"4.000000"},{"1":"Winthrop","2":"2017","3":"24","4":"6","5":"4.000000"},{"1":"Arizona","2":"2018","3":"27","4":"7","5":"3.857143"},{"1":"Florida St","2":"2019","3":"27","4":"7","5":"3.857143"},{"1":"Kansas","2":"2018","3":"27","4":"7","5":"3.857143"},{"1":"Michigan","2":"2018","3":"27","4":"7","5":"3.857143"},{"1":"Monmouth NJ","2":"2016","3":"27","4":"7","5":"3.857143"},{"1":"Nevada","2":"2018","3":"27","4":"7","5":"3.857143"},{"1":"St Joseph's PA","2":"2016","3":"27","4":"7","5":"3.857143"},{"1":"Abilene Chr","2":"2019","3":"23","4":"6","5":"3.833333"},{"1":"Grand Canyon","2":"2016","3":"23","4":"6","5":"3.833333"},{"1":"UC Davis","2":"2015","3":"23","4":"6","5":"3.833333"},{"1":"Duke","2":"2018","3":"26","4":"7","5":"3.714286"},{"1":"Hofstra","2":"2019","3":"26","4":"7","5":"3.714286"},{"1":"Houston","2":"2018","3":"26","4":"7","5":"3.714286"}],"options":{"columns":{"min":{},"max":[10]},"rows":{"min":[10],"max":[10]},"pages":{}}}
  </script>

</div>

Gonzaga *appears* takes the cake with the highest W/L ratio, 32.
However, I fact-checked this observation by searching for Gonzaga’s
2016-2017 season record online and it didn’t fully match up (Wins: 37,
Losses: 2; source:
<https://www.sports-reference.com/cbb/schools/gonzaga/2017.html>). I
spent some time searching for where the error may have been but I wasn’t
able to find it. I checked a few other team records and I was
consistently missing a few observations; we’ll just roll with it since
this is what I have to work with.

The next question I’m thinking about is: Did a team just have one really
good season? Virginia is only listed once in the top 10, and so I wonder
if they had one good season or if they’re also a good team on average.
I’ll remove the group\_by(season), that way I can look at the average
WL ratio for each team over the last 5 years.

<div data-pagedtable="false">

<script data-pagedtable-source type="application/json">
{"columns":[{"label":["name"],"name":[1],"type":["fctr"],"align":["left"]},{"label":["wins"],"name":[2],"type":["int"],"align":["right"]},{"label":["losses"],"name":[3],"type":["int"],"align":["right"]},{"label":["WL_ratio"],"name":[4],"type":["dbl"],"align":["right"]}],"data":[{"1":"Gonzaga","2":"148","3":"17","4":"8.705882"},{"1":"Villanova","2":"147","3":"23","4":"6.391304"},{"1":"Virginia","2":"137","3":"25","4":"5.480000"},{"1":"Kentucky","2":"140","3":"29","4":"4.827586"},{"1":"Kansas","2":"135","3":"32","4":"4.218750"},{"1":"Duke","2":"134","3":"34","4":"3.941176"},{"1":"Cincinnati","2":"131","3":"35","4":"3.742857"},{"1":"St Mary's CA","2":"124","3":"34","4":"3.647059"},{"1":"New Mexico St","2":"120","3":"34","4":"3.529412"},{"1":"Arizona","2":"130","3":"37","4":"3.513514"},{"1":"Wichita St","2":"123","3":"37","4":"3.324324"},{"1":"North Carolina","2":"130","3":"40","4":"3.250000"},{"1":"Michigan St","2":"128","3":"40","4":"3.200000"},{"1":"Purdue","2":"123","3":"42","4":"2.928571"},{"1":"Oregon","2":"124","3":"44","4":"2.818182"},{"1":"Belmont","2":"110","3":"41","4":"2.682927"},{"1":"Vermont","2":"117","3":"44","4":"2.659091"},{"1":"Maryland","2":"114","3":"45","4":"2.533333"},{"1":"Old Dominion","2":"116","3":"47","4":"2.468085"},{"1":"VCU","2":"119","3":"49","4":"2.428571"},{"1":"Houston","2":"113","3":"48","4":"2.354167"},{"1":"SMU","2":"113","3":"48","4":"2.354167"},{"1":"S Dakota St","2":"108","3":"47","4":"2.297872"},{"1":"Murray St","2":"103","3":"45","4":"2.288889"},{"1":"Buffalo","2":"112","3":"49","4":"2.285714"},{"1":"Xavier","2":"115","3":"51","4":"2.254902"},{"1":"Louisville","2":"111","3":"50","4":"2.220000"},{"1":"Michigan","2":"115","3":"52","4":"2.211538"},{"1":"Wisconsin","2":"114","3":"52","4":"2.192308"},{"1":"SF Austin","2":"98","3":"45","4":"2.177778"},{"1":"Dayton","2":"108","3":"50","4":"2.160000"},{"1":"ETSU","2":"105","3":"50","4":"2.100000"},{"1":"Nevada","2":"108","3":"52","4":"2.076923"},{"1":"BYU","2":"110","3":"53","4":"2.075472"},{"1":"West Virginia","2":"113","3":"55","4":"2.054545"},{"1":"San Diego St","2":"107","3":"54","4":"1.981481"},{"1":"Florida St","2":"108","3":"55","4":"1.963636"},{"1":"Utah","2":"102","3":"52","4":"1.961538"},{"1":"Baylor","2":"104","3":"54","4":"1.925926"},{"1":"Yale","2":"94","3":"49","4":"1.918367"},{"1":"Rhode Island","2":"105","3":"55","4":"1.909091"},{"1":"Davidson","2":"103","3":"54","4":"1.907407"},{"1":"Bucknell","2":"106","3":"56","4":"1.892857"},{"1":"Notre Dame","2":"108","3":"58","4":"1.862069"},{"1":"UC Irvine","2":"106","3":"57","4":"1.859649"},{"1":"Georgia St","2":"100","3":"54","4":"1.851852"},{"1":"Montana","2":"100","3":"54","4":"1.851852"},{"1":"Grand Canyon","2":"98","3":"53","4":"1.849057"},{"1":"Iona","2":"107","3":"58","4":"1.844828"},{"1":"St Bonaventure","2":"103","3":"56","4":"1.839286"},{"1":"Valparaiso","2":"98","3":"54","4":"1.814815"},{"1":"Arkansas","2":"107","3":"59","4":"1.813559"},{"1":"Iowa St","2":"105","3":"58","4":"1.810345"},{"1":"Miami FL","2":"103","3":"57","4":"1.807018"},{"1":"Butler","2":"102","3":"57","4":"1.789474"},{"1":"Seton Hall","2":"103","3":"58","4":"1.775862"},{"1":"MTSU","2":"101","3":"57","4":"1.771930"},{"1":"Louisiana Tech","2":"99","3":"56","4":"1.767857"},{"1":"Winthrop","2":"91","3":"52","4":"1.750000"},{"1":"Hofstra","2":"101","3":"58","4":"1.741379"},{"1":"Stony Brook","2":"98","3":"57","4":"1.719298"},{"1":"Ohio St","2":"103","3":"60","4":"1.716667"},{"1":"Wofford","2":"96","3":"56","4":"1.714286"},{"1":"Providence","2":"104","3":"61","4":"1.704918"},{"1":"SUNY Albany","2":"99","3":"59","4":"1.677966"},{"1":"UCLA","2":"102","3":"61","4":"1.672131"},{"1":"Texas Tech","2":"100","3":"60","4":"1.666667"},{"1":"Temple","2":"100","3":"61","4":"1.639344"},{"1":"Fresno St","2":"95","3":"58","4":"1.637931"},{"1":"Northeastern","2":"100","3":"62","4":"1.612903"},{"1":"Louisiana","2":"93","3":"58","4":"1.603448"},{"1":"Toledo","2":"98","3":"62","4":"1.580645"},{"1":"Boise St","2":"93","3":"59","4":"1.576271"},{"1":"Princeton","2":"84","3":"54","4":"1.555556"},{"1":"UT Arlington","2":"96","3":"62","4":"1.548387"},{"1":"Tennessee","2":"99","3":"64","4":"1.546875"},{"1":"Akron","2":"98","3":"64","4":"1.531250"},{"1":"FL Gulf Coast","2":"90","3":"59","4":"1.525424"},{"1":"Col Charleston","2":"96","3":"63","4":"1.523810"},{"1":"Illinois St","2":"96","3":"63","4":"1.523810"},{"1":"Kansas St","2":"99","3":"65","4":"1.523077"},{"1":"Oklahoma","2":"95","3":"63","4":"1.507937"},{"1":"Loyola-Chicago","2":"93","3":"62","4":"1.500000"},{"1":"Texas A&M","2":"96","3":"64","4":"1.500000"},{"1":"Virginia Tech","2":"97","3":"65","4":"1.492308"},{"1":"Tulsa","2":"94","3":"63","4":"1.492063"},{"1":"Florida","2":"98","3":"66","4":"1.484848"},{"1":"Kent","2":"95","3":"64","4":"1.484375"},{"1":"UAB","2":"95","3":"64","4":"1.484375"},{"1":"Hawaii","2":"89","3":"60","4":"1.483333"},{"1":"Indiana","2":"96","3":"65","4":"1.476923"},{"1":"Iowa","2":"96","3":"65","4":"1.476923"},{"1":"UNC Greensboro","2":"91","3":"62","4":"1.467742"},{"1":"LSU","2":"94","3":"65","4":"1.446154"},{"1":"Memphis","2":"98","3":"68","4":"1.441176"},{"1":"Marquette","2":"95","3":"66","4":"1.439394"},{"1":"Syracuse","2":"95","3":"66","4":"1.439394"},{"1":"Harvard","2":"82","3":"57","4":"1.438596"},{"1":"Sam Houston St","2":"86","3":"60","4":"1.433333"},{"1":"Northern Iowa","2":"92","3":"65","4":"1.415385"}],"options":{"columns":{"min":{},"max":[10]},"rows":{"min":[10],"max":[10]},"pages":{}}}
  </script>

</div>

Gonzaga, Villanova, and Virginia still come out on top with average W/L
ratios of 8.7058824, 6.3913043, and 5.48, respectively. These appear to
be some of the most winning teams, even on average.

### Tournament Win/Loss Record: 2015-2019

A few teams appear more than once in the table with the top 20 W/L
records over the last 5 seasons. Do these high W/L ratios translate to
high tournament performance? Let’s take a look:

<img src="MarchMadness_files/figure-gfm/Tournament W/L plot-1.png" style="display: block; margin: auto;" />

Above is a graph displaying teams with \>= 4 wins in a single tournament
between 2015-2019; meaning that they must’ve done at least decently well
in at least one recent tournament. The “count” is the total number of
wins and losses over the last 5 years for those teams. If we compare the
table and the graph we can get an idea of the teams with the top records
during the regular season and then compare that with how they performed
in tournaments. Interestingly, North Carolina has the highest cumulative
number of wins over the last 5 years in tournaments but they aren’t even
in the top 50 for regular season W/L records. Gonzaga’s, Villanova’s,
Virginia’s and Wisconsin’s tournament performance all coincides pretty
well with their respective W/L records, and Duke’s sort of does. Arizona
and Houston had some of the top records during the regular season, but
it apparently didn’t translate well to the tournament.

### FGP and Wins

Past W/L ratios would certainly be a good predictor of future W/L
ratios. What other predictors could potentially predict team wins? It
would make sense that higher field goal percentages leads to more wins.
Of course, it could also be true that higher field goal percentages are
a result of shooting less baskets overall, and making a higher
percentage of fewer shots. The relationship will likely give an idea of
which of these scenarios is actually occuring.

<img src="MarchMadness_files/figure-gfm/FGPCT plot-1.png" style="display: block; margin: auto;" />

Above is a plot where win proportion is binned into field goal
percentage groups. The count of wins and losses were totalled within a
field goal percentage range of 5% (ie. 20-25%), and then a proportion
for each group was calculated. As expected, there appears to be a
consistent relationship between field goal percentage and wins.

### Wins Throughout Season

Are wins and losses throughout a season “random”? In other words, do
losses occur randomly throughout a season, or are they clustered
together at a certain time? I’m not familiar with how basketball seasons
work, and so I don’t know if the same teams play each other repeatedly
at a certain point in the season or not. If they do, then this would of
course affect the “randomness” of wins and losses obersved.

<img src="MarchMadness_files/figure-gfm/WoT-1.png" style="display: block; margin: auto;" />

Above is a plot looking at when wins and losses occurred throughout the
season (2019) for several of the top teams, and I’ll be the first to
admit that it’s not the most aesthetically pleasing plot. There are a
few interesting patterns to note. Michigan had zero losses throughout
the first half followed by many losses in the second half. Were they
simply on a win streak? Did they play harder teams? Did they lose
motivation? Did a player get injured? Did the coaching staff change? Did
they switch up game strategies? Michigan St had an overall good season,
but they lost 3 games in a row about 2/3 of the way into the season.
What gives? Were they playing the same team all 3 times? Were they on
the road? Was a player injured? Could these patterns be explained by
other variables in the dataset? Maybe I’ll find out later this semester.
