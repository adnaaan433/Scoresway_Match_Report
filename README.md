# Scoresway_Match_Report

[Scoresway.com](https://www.scoresway.com/en_GB/soccer) is a great website where we can get the match event data of many other leagues which are not available in [whoscored.com](https://www.whoscored.com/)
So, here I have tried to make a post match report using the data from [Scoresway.com](https://www.scoresway.com/en_GB/soccer)

Guidelines:
1. Download the Scoresway.ipynb file, Opta Events.xlsx and Opta Qualifiers.xlsx files
2. Go to [Scoresway.com](https://www.scoresway.com/en_GB/soccer) and find the match you want to scrape
3. Inside the match, go to 'PLAYER STATS' tab
4. Right click anywhere and click Inspect
5. Go to the Sources tab
6. Then click the arrows beside api.performfeed.com > soccerdata > matchevent/xyz > click on the file here
7. Then you will see a lot of data, copy all of these(CTRL+A, CTLR+C)
8. Go to [konklone](https://konklone.io/json/) website and paste all the data
9. Remove last 2 brackets, then go all the way up and start finding the text "liveData": {, reomve all the text before this specicfic curl bracket, which has the text "liveData": before it
10. Then it will show the table of match event data, now Download the entire CSV
11. Then open the code, Run the first cell for importing the packages, and in the next cell you will find the instruction to put the csv file path and those .xlsx file path there
12. Then follow all the instruction for Pre-processing the data
13. After pre-processing is done following the instruction given there, Run all the codes below and you will get 2 pictures inside the 'Final VIZ' and 'Top Players Viz' group
 
