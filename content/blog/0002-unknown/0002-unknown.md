---
title: "Lessons in Project Planning and Risk Assessment Pt. 1"
date: 2021-07-13T23:52:24-04:00
Description: ""
Tags: ["planning"]
Categories: []
DisableComments: false
draft: true
---

The short: novice identifies showstopper hurdle *after* hundreds of human-hours have been expended. Project scrapped due to lack of feasible solution. Repeat a few times.

Hold on, I can explain. I have a laundry list of excuses readied up.

- I didn't understand the subject well enough until I had put the time that I did to know that the issue was as severe as it was.
- That's it. That's the only good excuse I have. Everything else is whiny or inaccurate.

I'm the type of person who doesn't like writing for the sake of writing. There should be a reason for an action. The projects that I undertake for my portfolio should be meaningful to me. They should solve a problem that I am currently experiencing in a novel way - if there's an adequate existing solution why should I re-invent the wheel?

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