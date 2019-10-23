---
layout: post
title:  "Challenges around DNS"
date:   2019-10-23 00:11:40
categories: netlify support
---
This is a great question because it’s something that not just non-technical users have issues with but also major corporations when launching new products. The first thing that I almost always have to decipher for someone confused by DNS is that purchasing domains, and controlling where they point is NOT web hosting. This is often confusing because many users will purchase a domain, pay a yearly or monthly fee, and think that’s all they need to put up their website. To make that even more confusing many large DNS providers often DO provide hosting for 1 free website when you purchase a domain, which confuses people even more. This is an education problem, but it seems to be persistent with almost all of my projects. 

The second major challenge I see with DNS has to do with propagation and caching. Launching a new website is exciting and often nerve wracking. When things go live, there is often a confusing period where some users will be reporting old behavior while DNS propogates around the world. While my experience is that it usually takes under 2 hours for DNS to fully propogate, there are often users that have caches or bookmarks that won’t forcibly request the new information, which can sometimes take a month for local caches to expire and to stop getting these types of requests. As DNS is a globally distributed and decentralized system, I see this being an ongoing issue into the future. 
