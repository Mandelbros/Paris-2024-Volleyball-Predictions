# Paris-2024-Volleyball-Predictions

The goal of this project is to predict the Volleyball results of the Olympic Games of Paris 2024, using Simulation and Machine Learning techniques. 

## Competition formula:
The volleyball competitions for women and men will each consist of two phases and a total of 26 matches per gender. 

Phases:
- Preliminary Phase: The competitions will begin with the preliminary phase, in which the 12 teams per gender will be divided into three pools (A, B and C) of four teams each. Every team will play against the three other teams in its pool. The top two teams from each pool and the two best third-placed teams will advance to the Final Phase. The Teams Combined Ranking System will be used to seed the teams in the Final Phase bracket.
- Quarterfinals: The top eight best-ranked teams as per the Teams Combined Ranking System will advance to the quarterfinals. The first-ranked team will play the eighth, the second-ranked team will play the seventh, the third-ranked team will play the sixth and the fourth-ranked team will play the fifth.
- Semifinals: The four winners of the quarterfinals per gender will advance to the semifinals. The winners of Quarterfinal 1 (1st vs. 8th) will play the winners of Quarterfinal 4 (4th vs. 5th), while the winners of Quarterfinal 2 (2nd vs. 7th) will play the winners of Quarterfinal 3 (3rd vs. 6th).
- Finals: The two winners of the semifinals will play the gold medal match to determine the gold and silver medals. The two teams that did not win the semifinals will play the bronze medal match to determine the bronze medal and fourth place.

For men, the qualified teams are:
- France
- Germany
- Brazil
- USA
- Japan
- Poland
- Canada

For men, the countries not yet qualified but ordered by world rankings up to May 16 2024 - 01:20 am UTC:
- Italy
- Argentina
- Slovenia
- Serbia
- Cuba

For women the qualified countries are:
- France
- Dominican Republic
- Serbia
- Turkey
- Brazil
- USA
- Poland

For women, the countries not yet qualified but ordered by world rankings up to May 15 2024 - 12:00 am UTC:
- China
- Italy
- Japan
- Netherlands
- Canada

Both for men and women, as an MVP, we will compute a grid with the probability that each country wins against each other country, based on recent historical results. Then we will simulate a specified number of posible tournaments using this data, and derive a ranking. Later on we will make more accurate predictions using specifics individual sets results, and simulations based on agents.
