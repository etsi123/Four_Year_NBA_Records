# Four_Year_NBA_Records

## **A brief walkthrough of modern basketball history through the lens of 4-year records.**

"There is winning and there is misery" - Bill Parcells

"Back in my day, XXX was better than this YYY". *Collective groan from anyone 30 years old or younger*. Without exaggeration, I think it is fair to say that we have all heard a phrase of this sort at least once in our lives. Some nostalgic person reminiscing upon "the good old days" in a way that disparages the present. I have heard this line used most frequently in the context of music and NBA basketball and while I may be willing to agree with the idea that the 80s was the golden age of music, I totally disagree with this as it pertains to basketball.

Let's try to objectively evaluate eras based upon sustained greatness: who were perennial championship contenders and winners? These teams should be in consideration for greatest teams of all time. The longer a team remains at the top, the greater the chance of winning championships and forming a dynasty. Therefore, let's see if we can learn anything by examining teams over 4 year increments rather than single years as it is typically done. The 82-game schedule was adopted in 1968 so we will begin this analysis in 1970 (mainly to be able to refer to periods of time in decade terms). Note that overlapping years were replaced with peak years during the same period (e.g., 2015-2018 Warriors are present instead of the 2016-2019 Warriors for 'mid 2000 Warriors'). The code to pull, manipulate, and analyze the historical win/loss data can be found in this github repo. Note that NBA seasons straddle 2 different years and, for convenience, I will refer to a season by the more recent year (e.g., the 2008-2009 Lakers would be referred to as the 2009 Lakers). 

Let's start by defining a nomenclature. Winning 65+ of 82 games in an NBA season shows dominance over the competition and is a strong predictor for a championship. In fact, 21 teams have won at least 65 games and 15 of those teams won the NBA championship. 60-65 game winners are also very competitive contenders, 55-60 game winners are serious contenders, 50-55 game winners are dark horse contenders, and 40-50 game winners are borderline playoff teams.  While cutoffs are somewhat arbitrary, they do need to be made somewhere and are indicated in Fig. 1. 

<p align="center">
<img width="286" alt="Avg_wins_label" src="https://user-images.githubusercontent.com/37279371/206335955-5f93f487-ae04-4447-96df-5959cf76361b.png">
</p>


<p align="center">
Fig 1. Historical rankings of teams based upon average wins over 4 years. 
</p>



As you can see from the results table (Fig. 2) or histogram (Fig. 3), teams often included in the discussion for "greatest team of all time" by NBA pundits are at the top - but one team emerges at the top by a wide-margin. The mid 2010's Golden State Warriors averaged 66.25 wins / year and won 3 of 4 NBA championships (and came within a Kyrie Irving step back 3 pointer of winning 4 of 4) between 2015 and 2018. This is 3.5 more wins / season than the second and third highest teams. Relative to their competition, no NBA team has ever been as dominant as the mid 2010s Golden State Warriors. Note, this is not solely because of the addition of Kevin Durant. The Warriors won the 2015 championship and the most regular season games (73) prior to acquiring Durant - a decision that ultimately solidified the Warriors as a nearly invincible juggernaut. They further showcased their sustained dominance at the turn of the decade as well, where they won another championship without Kevin Durant in the 2022 NBA season. 


<p align="center">
<img width="634" alt="Most_wins_table" src="https://user-images.githubusercontent.com/37279371/206336304-26b3a20f-9d94-471f-a34d-0eee663f1af3.png">
</p>

<p align="center">
Fig 2. Teams with the most wins over 4 years. Most basketball pundits would agree the featured teams are historically elite teams. 
</p>


<p align="center">
<img width="634" alt="hist" src="https://user-images.githubusercontent.com/37279371/206337934-92e9abd7-6d3d-49d2-aeb5-e9c8b07d8add.png">
</p>

<p align="center">
Fig 3. Histogram of sum of wins over 4 years. Perhaps unsurprisingly, an average team wins ~40 games / season  (~50% of their games). 
</p>

In the early 70s, two historically great teams emerged. Kareem Abdul-Jabbar and Oscar Robertson led the Milwaukee Bucks to 62 wins / season and solidified themselves as one of the top teams in basketball history. While dominant, they would only win 1 NBA championship during that stretch. The Boston Celtics amassed 61 wins / season during the same stretch and walked out of the 1980s with 2 NBA championships. Both legendary teams, but there was actually a great deal of parity in the NBA at that time with 8 unique champions during that decade - hardly a sign of sustained dominance. If an old-timer wanted to argue in favor of the apparent parity amongst the top teams, then they may have an argument in the 1980s. At their peaks, the Boston Celtics and Los Angeles Lakers each averaged 62.75 wins / season (tied for second all-time as of today) and faced each other in 3 epic finals (1984, 1986, and 1987). The 76ers also established themselves as a dominant force in the early 80s and have the 1983 NBA championship to show for it. Interestingly, the "Bad Boy" Detroit Pistons of the late 80s and early 90s averaged just 55 wins/season at their peak, far from the top, but were still able to dethrone the Celtics and Lakers and win back-to-back championships. In the 90s, the Chicago Bulls dominated the NBA and averaged 62.50 wins/season at their 4-year peak. Their closest competition during this stretch were the mid 90s Seattle Supersonics and Utah Jazz each with 60.25 wins / season on average. Importantly, the Seattle Supersonics and the Utah Jazz are the first team in the "Historically Great" category to fail to win an NBA championship during their historical stretch. 

The 2000s were an interesting time in basketball history. The Lakers and Spurs accounted for 7 of the 10 championships during that decade but only averaged 57.75 wins and 59.75 wins at their 4-year peaks respectively. Almost half of all teams averaging between 55 and 60 wins were from the 2000s, perhaps suggesting more championship contenders and diverse competition. However, the Spurs and Lakers often got the last laugh. In the 2010s, the Spurs continued their success and jumped into the historically great category with 61.25 wins, and have the 2014 NBA championship to show for it (and very nearly the 2013 NBA championship as well). The Miami heat walked out of the 2010s with 2 championships while only averaging 56 wins / season. They were soon joined by the aforementioned, legendary mid-late 2010s Warriors. 

### **Some other interesting points from the analysis:**

Let's examine some of the worst teams in NBA history as well. The first is the 90s Vancouver/Memphis Grizzlies who managed to win just 56 games in the mid 90s. In fairness to them, they were an expansion team and joined the NBA in 1995. The post Jordan-Pippen-Rodman-Jackson era was not a good one for the Bulls as they managed just 66 wins in the early 2000s. Fortunately for Bulls fans, this period could not take away what they had done during the 90s. Some other notable mentions on this list were the mid 2000s Sixers, who were unabashed in their attempts to tank to stock-pile draft picks and build for the future even selling it to their fans with the motto, "Trust the process". Despite some very strong Sixers teams in the late 2010s and early 2020's, they are yet to even make it to the conference finals let alone with the NBA championship. 

One of the great present day NBA basketball debates is "who is the greatest basketball player of all time, Michael Jordan or LeBron James?"" Even for objective, basketball pundits this isn't an easy question as it often comes down to what their team needs. If we look at accomplishments to answer the question, Jordan won 6 championships, 5 league MVPs, 10 scoring titles, and 1 defensive player of the year award (DPOY). Michael Jordan also prevented other historically great NBA teams from winning championships (specifically the Seattle Supersonics and the Utah Jazz). On the other hand, LeBron James has only won 4 championships, 4 league MVPs, 1 scoring title and 0 DPOYs. Furthermore, LeBron could not prevent historically great teams from winning as Jordan had done as he is just 2-5 against them all-time. Clearly, Michael Jordan is the more accomplished NBA basketball player. However, the reason this doesn't necessarily translate to the greatest NBA player of all time is that it is completely devoid of all context. Michael Jordan was on historically great teams himself where as LeBron wasn't. In fact, in the 5 losses to those teams his team was favored in none of them. Interestingly, the Cleveland Cavaliers had their 2 best 4-year stretches prior to LeBron's departure to Miami and upon his return. The Cavaliers averaged 55.5 and 52.75 wins/season during those stretches placing them in the upper-echelon of teams - although far from historically great. In his 4 year return to Cleveland, the Cavaliers made it to the finals 4 consecutive years winning 1 of them and losing the other 3 to the aforementioned Warriors team. In the 4 year absence, they amassed just 94 wins and accumulated 3 of the possible 4 number 1 overall picks. In the mid 90s, the Chicago Bulls managed to win 60.75 wins despite a 1.5 year hiatus from Michael Jordan, implying that the Bulls were an elite team even without Jordan. In fact, Chicago Bulls fans will often remind people that the 1994 Bulls were a missed call away from a 4th consecutive trip to the NBA finals despite the departure of Michael Jordan. Winning championships is often an amalgamation of circumstances and unfortunately for LeBron, he often found himself undermanned against historically elite teams. Advanced statistics such as RAPM support the notion that LeBron impacts winning more than any other player in NBA history, more information on this analysis can be found here. 




