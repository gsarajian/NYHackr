# NYHackr
Welome to my project! This was a proof of concepts of various applications of linear algebra and graph theory. This repository contains most of the files and exposition for the project. I gave a talk on these ideas at [NYHackr](https://nyhackr.org//?utm_source=rstatsai) (New York Open Statistical Programming Meetup) in April 2025, which you can watch [here](https://www.youtube.com/watch?v=uV0g4zT4yEc). I sprinkled some motivation and jokes in the talk, but the heart of the content surrounded the two subprojects below:

## NCAA Basketball Rankings
The first subproject sought to rank the hundreds of Division I NCAA basketball teams solely based on the the scores of the thousands of games between the teams. I ended up looking at two methods:
- [This](https://yetanothermathblog.com/2016/12/03/sports-ranking-methods-1/) implementation of Massey's method
- [This](https://yetanothermathblog.com/2017/01/26/sports-ranking-methods-3/) implementation of PageRank

The raw data came from [here](https://masseyratings.com/scores.php?s=cb2025&sub=ncaa-d1&all=1&sch=1) and a cleaned version is provided within the repository. The top 25 ratings from Massey's method and the PageRank method are:

Massey's:
| Rank | Team    | Estimate for rating      |
| ---- | ------------- | ------------- |
|  1   | Duke        | 21.19 |
|  2   | Auburn      | 19.10 |
|  3   | Houston     | 19.00 |
|  4   | Florida     | 18.38 |
|  5   | Gonzaga     | 17.80 |
|  6   | Texas Tech  | 17.57 |
|  7   | Arizona     | 17.25 |
|  8   | Maryland    | 17.07 |
|  9   | Iowa St.    | 16.78 |
|  10  | Alabama     | 16.63 |
|  11  | Tennessee   | 16.13 |
|  12  | Illinois    | 15.96 |
|  13  | Baylor      | 14.87 |
|  14  | Kansas      | 14.73 |
|  15  | Missouri    | 14.74 |
|  16  | Kentucky | 18.38 |
|  17  | Duke    | 21.19 |
|  18  | Auburn  | 19.10 |
|  19  | Houston | 19.00 |
|  20  | Florida | 18.38 |
|  21  | Duke    | 21.19 |
|  22  | Auburn  | 19.10 |
|  23  | Houston | 19.00 |
|  24  | Florida | 18.38 |
|  25  | Florida | 18.38 |

## Connected Musicians
The second subproject looked at collaborations between musicians and asked which musicians are the most "connected" in various senses. I looked within various genres and filtered for different levels of popularity and ranked the musicians based on some of the types of centralities which you can read about [on Wikipedia](https://en.wikipedia.org/wiki/Centrality).

The data came from [Kaggle](https://www.kaggle.com/datasets/jfreyberg/spotify-artist-feature-collaboration-network). 

Feel free to reach out with any questions or comments!

