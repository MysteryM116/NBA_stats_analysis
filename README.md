# NBA players' performance analysis
This is a statistical analysis testing the hypothesis whether life experiences have an incremental impact on an athletes' statistical performance. In here, I focused on the performance of pro players from National Basketball Association (NBA). The data I used here were scrapped from https://www.basketball-reference.com.
<br>
### Framework
● Life experience is defined as either an engagement, marriage, divorce, birth/adoption and death of a family membber. <br>
● This is a time cound study where the performance of the players were compared as the month before and the month after the event. 

### Game performance stats
For example, Dwayne Wade, SG for the Miami Heat, became engaged to actress Gabrielle Union on December 21, 2013. Performance stats from each game within on month before and after Dec 21, 2013 were scrapped, and below is a visualization of the number of field goals, 3-pointers, free-throws, rebounds, assists, turnovers and personal fauls. The time 0 on the x-axis represents the date of the event and negative numbers are the days before the event while the positive numbers mark the number of days after the event. <br>
![screenshot from 2018-07-15 20-38-02](https://user-images.githubusercontent.com/30357662/42740018-2547f872-886f-11e8-8f0a-28c58bfdb246.png)
The changes in performance are not quite clear from these simple performance stats, but there are more complicated ones and balanced all the aspects of a game. These scores were normalized bu subtracting the average performance over two months. It became clear that the blue bars (below average performance) are more frequent after the events. 
![screenshot from 2018-07-15 20-38-21](https://user-images.githubusercontent.com/30357662/42740135-d1e5a42a-8870-11e8-820c-ec29a2585dce.png)

