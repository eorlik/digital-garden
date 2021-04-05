---
title: Online misinformation
updated: '2021-04-01'
---

Two years ago I started working on internet policy for the UK government with what I thought was a very clever idea for squishing misinformation on social media at scale. I was quite pleased with this idea, reasoning that it would:
- reduce the spread of misinformation on social media platforms...
- ...without eradicating it completely.<label for="sn-1" class="margin-toggle sidenote-number"></label>
<input type="checkbox"
       id="sn-1"
       class="margin-toggle"/>
<span class="sidenote">
    Leaving up a trace of misinformation seems like a good idea for two reasons - the first being that IRL there's plenty of false info and we shouldn't deny that, and the second reason is that if users see that if they share misinformation it gets less engagement than high quality content, then they'll be nudged towards trying to share more of the latter.
</span>
- It would train users to be more judicious when they shared information. Something that machine-learning based moderation systems don't prioritise.
- It could reasonably be described as  _ex-ante_ 'democratic', not relying as Facebook and Twitter do on a shoot-first-ask-later approach which involves sometimes incorrectly moderating posts and waiting for user to complain before acting more fairly them (or otherwise serving 'justice', whatever you take that to mean.) It can also be completely transparent in its working – as it ought to be!

### So what's the big idea?

I've flippantly called this solution *networked meat-based intelligence*, which is both a reference to the human minds that are the main driver of viral misinfo and, I'm hoping, the solution as well. I suppose I'm also having a dig at Silicon Valley's love affair with machine learning as the solution to all our problems, which I think overlooks the ability of communities to solve their own problems, if they're empowered and helpfully configured.

This idea if based on a few main assumptions. There may be strong evidence for or against these assumptions, but I can't think of any right now.
1. Critical thinking skills are in themselves an effective prophylactic against misinformation.
2. Most online social groups have at least a few tip top critical thinkers.
3. People can be [conditioned through repetitive rewards](https://www.youtube.com/watch?v=erhmslcHvaw) to take more care of the information they share online. In this case the reward is the dopamine hit of seeing people like your social media post.

**The basic idea** is that you can identify your best critical thinkers based on their historic behaviour – what they share, and how often – and give their content more visibility in the feed. Likewise, if a user historically shares a lot of bullshit then as a matter of course you demote their content. This would both increase the quality of information sitting at the top of people's news feeds, and give an incentive for users to share more of that information, as it drives visibility of, and engagement (likes and comments) with their content.

The way you'd do this is by employing a team to manually code the most hundred or so most-shared articles in an information space<label for="sn-2" class="margin-toggle sidenote-number"></label>
<input type="checkbox"
       id="sn-2"
       class="margin-toggle"/>
<span class="sidenote">
        I'm not sure how to define an information space. I had thought of it being defined by where a user lives, but there may be a smarter way of drawing a line around virtual communities.<br><br>
</span>, scoring them on a misinformation index<label for="sn-3" class="margin-toggle sidenote-number"></label>
<input type="checkbox"
       id="sn-3"
       class="margin-toggle"/>
<span class="sidenote">
        This needs to be politically neutral, and I envisioned it being based on the coherence of the articles (does the headline accurately sum up the content?), its transparency (do they cite their sources?) and meta-data (does the source have an editorial code?). Equally, organisations like the [Global Disinformation Index](https://disinformationindex.org/) have their own methods which could work.
</span>, and then keeping and eye on who shares what. People who share high-scoring content are your bullshit detectors, etc, and you can score users according to their customary approach to sharing.

The nice thing about giving users scores (which they can improve by taking more care over what they share) is that you can then infer the quality of information which *hasn't* been manually coded based on who shared them. If a new article is shared by a BS-detector, give it a high integrity score. If it's then shared by someone with a low score, then take a few points off the article's integrity score.

### Will it work?

No idea - if I knew how to use Twitter's API, and had the time and coding/statistical skills to scrape the most shared links in a month, score them and then play the whole thing out then I would... but I don't.

### If it's such a good idea why isn't Facebook doing it?

Maybe it would eat into their profits?