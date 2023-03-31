# i310d-assignment10

Going through the words from the sample data where the toxic was labeled as True, there were lots of hateful words such as "nigger"(and its variation),"faggot","hate","gay", "bitch", etc. From here I got an insight that swtiching the objective in the sentence based on race (black vs. white) might cause a bias in the model. For exmaple, when I enter "I hate white people", I get 0.82 for the toxic score; while the score is 0.854 for "I hate black people." 

Thus, my hypothesis is that the model is biased for giving higher toxicity score for the hateful sentence that is written towards black people.

Going through 15 freshly written hateful sentence (swiching only race between Black and White for each case), I conclude that when the sentence is writeen towards black people, it gets higher toxicity score compared to when it is written toward white people. Except the race, no single word was modified. The mean score for sentence for Black people was 0.695 while the mean score for sentence for White people was 0.643. For every sentence, the model decided that it is either same or more toxic when it was for Black instead of White.

One possible reason that the model decides the hateful sentence written toward Black people is more toxic is because Black people have their history of hates and segregations, so that it is common to have more sensitivity towards toxic contents when it comes to them. The same logic might go along with other races or other minorities such as Men vs. Women.
