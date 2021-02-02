# ipl-analysis-hadoop


<b>Analysis of IPL data using Hadoop</b><br><br>
Bigdata analytics plays and important role in every scenario even in sports.IPL(Indian Premier League) is a professional Twenty20 cricket league in India established by the Board of Control for Cricket in India (BCCI) in 2007.
<br><br>
IPL Analysis is an good example how BigData analytics is important in sports.This Analysis helps teams to pick players in Auction to thier team.Based on different parameter analysis helps to select players and build a balanced team.<br><br>
Few Parameters to Select Batsman :<br>
i. Consistency <br>
ii. Strike Rate (Fast Scoring Ability)<br>
iii. Hard Hitting Ability  IPL<br>
iv. Running Between wickets<br>

All the above parameter are caluclated and analysed Using <b>Hadoop MapReduce</b> based on historical ball by ball data available from year 2008 (start of IPL Season 1) to 2020 (IPL Season 13). 

<b>resources</b> Folder contains IPL ball by ball dataSheet.<br>
<b>src</b> Folder contains MapReduce programs written for analysis of particular parameter.<br>
<b>lib</b> Folder contains libraries required to run programs written in src folder.<br>
<b>output</b> Folder contains outputs of the <b>analysed data and details</b> based on the criteria.<br>

Data Source  From <a href="https://cricsheet.org/downloads/#experimental" target="_blank">CricSheet</a>.<br>
Concept of Analysis From <a href="https://www.firstpost.com/long-reads/ipl-and-big-data-analytics-a-match-made-in-heaven-4438611.html" target="_blank">FirstPost</a></br>

Above Analysis in Spark Core - <a href="https://github.com/durga-mahesh-333/ipl-analysis-spark" target="_blank">ipl-analysis-spark</a>

