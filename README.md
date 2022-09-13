# Coordination-Detection
1.	Detecting Inauthentic Behaviour in Political Online Conversations (Python-networkx, communityLouvain,igraph,matplotlob,pandas,plotly, Gephi):

    I suggested a network strategy to locate coordinated social media accounts. In order to show how mymethod may be used to identify various forms of coordination on Twitter, I offered two case examples one being screen handle sharing and other, hashtag narrative. My method tries to identify coordinated actions at the society level, as opposed to supervised approaches that assess the attributes of individual users to assess the odds that an account is a bot or not. The identification and characterization of hostile accounts using my technique may then be utilised to train supervised learning systems.
    •	Unsupervised network-based technique using dynamically generated behavioural traces, such as hashtag sequences and shared screen names between accounts to detect coordinated behaviour among users. 
    •	For hashtags, I have tried to follow the flow of hashtags through the course of one year from 27th August 2018 to 2nd September 2019. The patterns showed that the hashtags repeated for several days contributing to various narratives being formulated through the year. 
    •	The screen handles were analysed for a year’s Twitter data and there were clear clusters of users sharing screen names indicating coordinated behaviour. 
    •	I used Google colab pro to develop the logic to form graphs and communities with the help of libraries like networkx, community Louvain algorithm, igraph, plotly. For visualization of graphs and further filtration, I used Gephi tool.
    
Main Findings:
Hashtags Narrative:
    For instance, the hashtag #bolsonaro17 has been used for more than 100 days and has been active for a considerable amount of time. In the above       enlarged cluster as well, the hashtags point to Sergio Moro and President Bolsonaro. Hashtags such #ciro and #lulalivre #haddad have also remained consistent across the days spanning from day 8 to day 58. They were then paused for a few days and then resumed the scattered usage from day 60 to day 204.    It can be observed that those who favour or oppose presidential candidates like Bolsonaro, Lula, Ciro, and Haddad intensified
their tweets with such hashtags, especially in the latter half of the year as the presidential election season in some areas of Brazil got nearer. The hashtags which are associated with other parallel communities are for instance, supporters of Bolsonaro(#bolsonaro17) who engaged with supporting the United right party(#direitaunida) which is the current ruling party and the former judge Sergio Moro (#somostodossergiomoro). The ruling party supporters also sided with people who were against Lula and amplified the hashtags (#lulapreso). There were also hashtags which sided with the supporters of the project #escolasempartido (No party School).

Screen Handle sharing:

The total communities formed from the data was 52. After filtering the edges wherein, I used the filter which had more than 3 edges, found that the number of nodes and edges were, 142 and 202 respectively. One peculiar thing to observe is that these handles is that they are not only suspended or do not exist now as the users/ supporters
Number of accounts: 5 No of handles:12 Min Switches: 0 Max switches: 8
of President Jair Bolsonaro used names of famous athletes like Messi (@bolsonaromessi) to attract more users to “follow them back”, indicating, that the user might be with the intention that the public may visit his/her page and the user may be able to garner responses from the general public indulging in something known as username squatting or impersonation. Username Squatting refers to the unethical use of username profiles on social networking sites to pretend to be someone else. Typically, name squatting entails the acquisition of a certain username / account handle with malice aforethought. The accounts also acquired screen handles like @sergiomoronews, @carlosbolsonaro, @gabrielahardt. Sergio Moro, a former judge, and Gabriela Hardt who is a current judge, whereas Carlos Bolsonaro is the son of the Brazilian President Jair Bolsonaro. Sergio and Gabriela had passed judgements against the former imprisoned President Lula and sided with the current ruling party of Jair Bolsonaro. The user accounts acquired by this one user indicates that it wants to amplify the posts related to the current ruling party and the people associated with them in the ruling government. When I searched these accounts on Twitter, I found that they had been suspended by the platform and were part of dubious behaviour.
   
