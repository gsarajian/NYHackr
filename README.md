# NYHackr
Welome to my project! This was a proof of concepts of various applications of linear algebra and graph theory. This repository contains most of the files and exposition for the project. I gave a talk on these ideas in the [https://nyhackr.org//?utm_source=rstatsai](New York Open Statistical Programming Meetup) in April 2025, which you can watch [https://www.youtube.com/watch?v=uV0g4zT4yEc](here). I sprinkled some motivation and jokes in the talk, but the heart of the content surrounded the two subprojects below:

## NCAA Basketball Rankings
The first subproject sought to rank the hundreds of Division I NCAA basketball teams solely based on the the scores of the thousands of games between the teams. I ended up looking at two methods:
- This implementation of Massey's method: https://yetanothermathblog.com/2016/12/03/sports-ranking-methods-1/
- This implementation of PageRank: https://yetanothermathblog.com/2017/01/26/sports-ranking-methods-3/

The raw data came from [https://masseyratings.com/scores.php?s=cb2025&sub=ncaa-d1&all=1&sch=1](here) and a cleaned version is provided within the repository.

## Connected Musicians
The second subproject looked at collaborations between musicians and asked which musicians are the most "connected" in various senses. I looked within various genres and filtered for different levels of popularity and ranked the musicians based on some of the types of centralities which you can read about [https://en.wikipedia.org/wiki/Centrality](on Wikipedia).

The data came from [https://www.kaggle.com/datasets/jfreyberg/spotify-artist-feature-collaboration-network](Kaggle). 

Feel free to reach out with any questions or comments!

