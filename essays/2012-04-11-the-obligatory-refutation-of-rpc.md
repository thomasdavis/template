---
layout: post
title: The obligatory refutation of RPC (Meteor.js)
date:   2012-04-11
permalink: the-obligatory-refutation-of-rpc
---

**Note: This is a very old blog post from my younger years**


I have just been reading through all the discussion of Meteor.js on Hackernews and noticed that the discussion had very little critique.   So here are just a few articles to think about and at the very least this post hopes to facilitate some discussion of the cons of the Meteor.js approach. 

----

[REST：An Alternative to RPC for Web Services Architecture](https://docs.google.com/viewer?a=v&q=cache:LylgA_fL8q4J:web.uvic.ca/~erikj/seng422/resources/rest_paper.pdf+&hl=en&pid=bl&srcid=ADGEESjYHfPLfpUiFhk4xLz6u9tSLXyTtcs6RVvV9ZdSqcNFjPNZ6iKmU5N7Ij0kYphZXmEqAL0VvVYGE9kT14vn7SveDWswWyL71LXn2neko4XEiM5PKaV_ZP5pH2kksIpaPgtcTgmA&sig=AHIEtbSBz804J-e96OlGr7I-LyV4ZDiLBQ&pli=1)

As a front-end developer this publication articulates well some of my strongest concerns. 

----

[Now.js released on Hackernews - 400 days ago](http://news.ycombinator.com/item?id=2316005)

A user `jerf` gives an indepth critique and should proove a valuable insight.

----

[Erlang - This the road we didn't go down](http://armstrongonsoftware.blogspot.com.au/2008/05/road-we-didnt-go-down.html)

More food for thought

----

### My thoughts

I just wrote this up in a matter of minutes so can't do the duty of clarifying any refutations.

Though my quick points would be

* Clients are now more tightly coupled to servers and actually influence the servers development
* Versioning of data/API's becomes more complex
* Security becomes more complex
* We should be striving towards improving our understanding of REST to tackle the problems or at least theorizing how RPC can solve them.
* [Now.js](http://nowjs.com/) and [dnode](https://github.com/substack/dnode) have been around for a while now.  They have already managed to grow a culture of negative sentiments

Hopefully some experts chime in and give us the other side of the story

Thanks for reading!
