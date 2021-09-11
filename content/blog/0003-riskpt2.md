---
title: "0003 Riskpt2"
date: 2021-09-11T01:02:05-04:00
Description: ""
Tags: ["planning"]
Categories: []
DisableComments: false
draft: true
---


In December of 2020 I began outlining the first project related to one of my passions - Valorant eSports. Valorant is a competitive 5 on 5 tactical shooter which requires high levels of individual talent as well as team co-ordination, much like it's inspirational antecedent CounterStrike. Riot, the game developer, has a well documented API that allows for the retrieval and analysis of online match data. By this time, there were already many tools for statistical analysis of gameplay, approaching the game similar to an analyst would football or baseball. This allowed players, both amateur and professional, to better themselves by identifying factors that affect their performance, both individually and as a team.

These tools allowed for players to identify *quantifiable and technical* mishaps (i.e. mechanics, strategy or tactics). However, given the co-operative nature of the eSport, communication plays a significant role in team performance. Outside of having a coach listen in or performing a review of recorded gameplay, there wasn't an easy way of identifying issues in communication or co-operation.

My project was to design a tool that allowed for the analysis of team communications to identify shortcomings and provide feedback. I wanted something that could help with the *mental* aspect of a competitive environment.

Immediately, a series of design choices and technical challenges were apparent. I had to narrow the scope down to have an idea where to begin. I chose to limit the project to audio analysis only - no screen recordings. This reduced the data to analyze but made analysis potentially more difficult.

After looking at what technologies were available, I had a semblance of a plan. From the audio file, I would determine:

- A timeline of events that occured in game, (Very Hard)
- A transcript of communications spoken by members of the team (Easier)
- What tone of voice (positive, negative) was used for each phrase of speech. (Also Easier)

Then came the kicker - what ultimately caused the folding of the project. Since I'm not someone who has credentials to critique these elements of gameplay (i.e. not a pro player, not a performance coach, etc.), I thought the most appropriate way of legitamizing the project would be to leverage machine learning[^2]. 


[^2]: Yes, I know that sounds like a start-up pitch from the early 2010s.