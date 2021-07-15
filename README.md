# zedGemFinder

With the many factors affecting horses in Zed it is important to have an understanding of each of these factors in order to make informed decisions. For this particular report, we are looking to find Gems from horses that have a racing history. Though owners of these horses should already know the quality of their horse given the history, it is certainly possible they do not know the full extent to that horses’ quality: whether or not it is a Gem. To identify Gems in the data we have used the following variables to design our query:

**Odds**: Has an average odds less than or equal to the average fourth place odds

**Place Pct**: Finishes first, second, eleventh, or twelfth 40 percent of the time

**Race Time**: Has an average finish time greater than or equal to one standard deviation from the average finish time of all Zed Horses

This notebook slices through the data from Know Your Horses and https://zed-odds.netlify.app/ in order to find horses that are what the Zed community calls gem racers.
