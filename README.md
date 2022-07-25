# Wordle_Simulation

 ***************************************************************************************************
 
Kanji_simulator.py - 
 
Uses SM2 algorithm, a spaced repetition scheduling module which schedules items to learn or memorise(in our case, Japanese Kanjis), depending on how easily a player recalls the learnt card.
We simulate random scores for each kanji and schedule kanjis to be learnt according to this.
Scores are sampled from a Chi-square distribution.
Running the Simulation for a fixed period will tell the number of kanjis learnt within that period for a particular user.
Parallely, we could run a simulation to check when all the Kanjis can be learnt for a particular user.
A kanji is said to be learnt when a particular user scores a perfect 5 on two consecutive attempts.
Running the simulation for 10 users, an average period of 10 years was recorded to learn all the Official 2136 Kanjis in the Japanese alphabet.

NOTE:
All kanjis are treated as the same, and of the same difficulty, which might not be representative of true learning.
Moreover, scores for each test, are randomly generated from a chi-square distribution whose parameters remain unchanged with number of revisions of same kanji.
This is an abstraction from reality, as people tend to remember more of what they revised, and have a higher chance of recalling those that they have learnt more.
User profiles have also not been taken into account.
In reality, different users may have different memory skills enabling them to remember more or less.
However, here each user score is generated from the same underlyiing distribution.

 ***************************************************************************************************
 
 Created by Bharath Ravilla Kumar, Srijit Saha, and Moumi Roy.
