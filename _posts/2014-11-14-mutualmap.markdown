---
layout: post
title:  "mutualmap [Rails, d3.js]"
date:   2014-11-14 21:23:29
categories: portfolio
cover_photo_url: /images/mutualmap.png
main_offsite_link: "https://mutualmap.herokuapp.com/graph/1"
---

# Project links

**Live site:** [MutualMap](https://mutualmap.herokuapp.com/graph/1)  
**Source:** [MutualMap source on GitHub](https://github.com/a17levine/facebookfriendmap)

# How do strangers meet at a party?

I set this project up to address this problem in a fun way. By figuring out who at the party shares mutual friends with you on Facebook, you can strike up conversations. If a stranger and I both know Jess, I could say "Hi I'm Alex. I noticed from MutualMap that you know Jess, how do you know her?"

# How it works

When you show up to a party, there is a check-in laptop and a computer projecting the fun web of connections constructed using a D3.js Force Layout. The app uses the Facebook JavaScript API to authenticate and then passes your authentication token to the server.

The server slurps all of your friends to the database and then compares them to the friends of the others at the party. When matches are calculated, the graph is redrawn and you are given a personalized view of people with whom you share mutual friends.