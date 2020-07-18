# Page-Rank-Algorithm
##### Case 1: Imagine we have 100 Procrastinating Pats on our micro-internet, each viewing a single website at a time. Each minute the Pats follow a link on their website to another site on the micro-internet. After a while, the websites that are most linked to will have more Pats visiting them, and in the long run, each minute for every Pat that leaves a website, another will enter keeping the total numbers of Pats on each website constant. The PageRank is simply the ranking of websites by how many Pats they have on them at the end of this process.

##### Case 2: We add a small probability that the Procrastinating Pats don't follow any link on a webpage, but instead visit a website on the micro-internet at random. We'll say the probability of them following a link is  d  and the probability of choosing a random website is therefore  1−d . We can use a new matrix to work out where the Pat's visit each minute.

## M = dL + ((1−d)/n)J

###### where  J  is an  n×n  matrix where every element is one.

##### If  d  is one, we have the case we had in previous case, whereas if  d  is zero, we will always visit a random webpage and therefore all webpages will be equally likely and equally ranked. For this extension to work best,  1−d  should be somewhat small.
