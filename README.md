# Recommeder Project
Group Members: Yerline Herrera, Faustina Nyaung, and Jonathan Huang

## Summary:
Our group chose to study and explore Skill Estimation to estimate players’ Starcraft II
skill level and predict game outcomes between two players. To achieve that, we used pyGM to
model skill as a discrete variable based on win/loss data. We assumed that higher skilled players
in Starcraft II had a better chance of winning. We also constructed a table of win probabilities
given players’ skill levels in different matchups. To study the best technique for skill estimation,
we compared our algorithm with a simple skill estimation approach that calculates a player’s
skill level as a fraction of games they have won in the past, in comparison to the amount of
games they have played. This allowed us to study how much more accurate skill estimation can
be if we rank users’ skill level and compute win probabilities for each player. To further test the
accuracy of our skill estimation algorithm, we also conducted different tests using different
amounts of training data scores to see how much training data is actually necessary for us to
calculate a similar amount of correct predictions as when we utilize the full dataset. We chose to
study this problem because we noticed it takes a really long time for our model to factor the full
dataset and wanted to see if we could minimize this problem because we would ideally not like
to spend a lot of time running estimation code on big data.

Please refer to our pdf report for our final findings.
Current UCI students, please do not copy our project as that is considered plagiarism.
