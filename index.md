---
layout: default
title: The MeToo movement
subtitle: A story telling through data
---

<center>
  
<h1> The #MeToo movement : a story telling through data </h1>

</center>

<center>
{% include wordcloud.html %}
</center>

<br>

<div style="text-align: justify">
  
  The aim of this project is to use a dataset of tweets containing #metoo and associated hashtags, in order to analyze this movement and better understand it.
  
  <br><br>
  
  The #MeToo movement is a global movement against sexual abuse. It spread virally in October 2017 as a hashtag used on social media in order to show the widespread phenomenon of sexual harassment, particularly in the workplace. The idea is to fearlessly talk about any sexual abuse one might experience and to rebel against the culture of staying silent after going through such traumatising experiences. A lot of celebrities participated in this movement by highlighting their stories on social media, including renowned actress, personalities, and politics, but also persons from simple backgrounds. As a team we are motivated to understand the movement because of its intensity and controverse. It is a challenge to put aside our personal opinion as individuals and consider only the data around this thematic to arrive to an interesting yet objective datastory.
  
  <br><br>
  
</div>
  
<br>
  
<center>
  
<h1> Explore the movement timeline </h1>

Please select a hashtag to visualize the associated activity on Twitter.

{% include buttons.html %}

<br><br>

<h1> Tweeting is sharing </h1>
  
<br><br>

<div style="text-align: justify">

  <img src="/img/newplot.png" alt="Retweet percent" style="max-width: 300px;" ALIGN="right" HSPACE="30"/> An important thing to notice is that - as in a lot of movements on Twitter - most of these tweets are actually retweets. Indeed, it is the case for almost 3 tweets over 4. Thus, in any cases, we cannot talk about isolated testimonies. It shows that this mobilization is over all a process of sharing stories of others by showing support or disagreement. Twitter hence enables the connection of persons worldwide to develop a base and gain awareness to the cause. This can be also criticized : it raises the question of stacktivism, which happens when people show support for a cause with the main purpose of boosting the egos of participants in the movement, by simple actions ("like", "retweet"...) that require very little thought or effort. 
  
</div>

<br><br>

Here are the tweets in our dataset that has been the most retweeted.

<br><br>

<blockquote class="twitter-tweet" data-lang="fr"><p lang="en" dir="ltr">The 16 women who accused Trump of sexual assault are telling their story in one video-please share this far &amp; wide. RT if you agree it’s time for Trump to be held accountable for his sexual misconduct.<a href="https://twitter.com/hashtag/TrumpSexPredator?src=hash&amp;ref_src=twsrc%5Etfw">#TrumpSexPredator</a> <a href="https://twitter.com/hashtag/AMJoy?src=hash&amp;ref_src=twsrc%5Etfw">#AMJoy</a><a href="https://t.co/hNIqZEI54G">pic.twitter.com/hNIqZEI54G</a></p>&mdash; Scott Dworkin (@funder) <a href="https://twitter.com/funder/status/932703161596432384?ref_src=twsrc%5Etfw">20 novembre 2017</a></blockquote>

<br><br>

<blockquote class="twitter-tweet" data-lang="fr"><p lang="en" dir="ltr">I mean, what world are we living in that an accused sexual abuser is allowed to be our President and an accused pedophile is allowed to run for senate? These two things have many things in common - one of which - is the Republican National Committee. <a href="https://twitter.com/hashtag/MeToo?src=hash&amp;ref_src=twsrc%5Etfw">#MeToo</a></p>&mdash; Alyssa Milano (@Alyssa_Milano) <a href="https://twitter.com/Alyssa_Milano/status/938186096080506882?ref_src=twsrc%5Etfw">5 décembre 2017</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<br><br>

<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> <blockquote class="twitter-tweet" data-lang="fr"><p lang="en" dir="ltr">Just reported <a href="https://twitter.com/Rosie?ref_src=twsrc%5Etfw">@Rosie</a> for targeted harassment, mainly to see if Twitter does indeed have a double standard. Everyone knows if Rosie were conservative, Twitter would suspend her in a hot second. So, Twitter, put your money where your mouth is. <a href="https://twitter.com/hashtag/MeToo?src=hash&amp;ref_src=twsrc%5Etfw">#MeToo</a></p>&mdash; Ben Shapiro (@benshapiro) <a href="https://twitter.com/benshapiro/status/944220986525618176?ref_src=twsrc%5Etfw">22 décembre 2017</a></blockquote>

<br><br>

<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script><blockquote class="twitter-tweet" data-lang="fr"><p lang="en" dir="ltr">I talked to a girl who says she went on a date with <a href="https://twitter.com/azizansari?ref_src=twsrc%5Etfw">@azizansari</a> in an exclusive for <a href="https://twitter.com/babedotnet?ref_src=twsrc%5Etfw">@babedotnet</a>. She told me, &quot;It was by far the worst experience with a man I’ve ever had.&quot; I believe her. <a href="https://twitter.com/hashtag/TimesUp?src=hash&amp;ref_src=twsrc%5Etfw">#TimesUp</a> <a href="https://twitter.com/hashtag/MeToo?src=hash&amp;ref_src=twsrc%5Etfw">#MeToo</a> <a href="https://twitter.com/hashtag/AzizAnsari?src=hash&amp;ref_src=twsrc%5Etfw">#AzizAnsari</a> <a href="https://t.co/p7q0fjSsh0">https://t.co/p7q0fjSsh0</a></p>&mdash; Katie Way (@k80way) <a href="https://twitter.com/k80way/status/952327321431756801?ref_src=twsrc%5Etfw">13 janvier 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<br>

<h1> Topic clustering </h1>

<br>

{% include topic_clustering.html %}

<br>

<h1> Sentimental Analysis on All Tweets </h1>


<h1> Context Analysis All Tweets </h1>

<br>

<img src="img/icons/family.png" title="Family" width="50"/> &nbsp; <img src="img/icons/friends.png" title="Friends" width="50"/> &nbsp; <img src="img/icons/religion.png" title="Religion" width="50"/>  <img src="img/icons/leisure.png" title="Leisure" width="50"/>  &nbsp; <img src="img/icons/work.png" title="Work" width="50"/> &nbsp; <img src="img/icons/home.png" title="Home" width="50"/>

<br>

{% include pieplotContext.html %}

<br>

<h1> Thematics Analysis All Tweets </h1>
<br>

<img src="img/icons/bio.png" title="Biology" width="50"/><img src="img/icons/body.png" title="Body" width="50"/> &nbsp; <img src="img/icons/social.png" title="Social" width="50"/> &nbsp; <img src="img/icons/health.png" title="Health" width="50"/> &nbsp; <img src="img/icons/human.png" title="Humans" width="50"/> &nbsp; <img src="img/icons/death.png" title="Death" width="50"/> &nbsp; <img src="img/icons/sexual.png" title="Sexual" width="50"/> &nbsp; <img src="img/icons/money.png" title="Money" width="50"/>

<br>

{% include pie_chartThematics.html %}

<br>

<h1> Implication, Group Dynamics and Certitude Analysis All Tweets </h1>

<br>

<img src="img/icons/hear.png" title="Hear" width="50"/> &nbsp; <img src="img/icons/cogmech.png" title="Cognitive Mechanisms" width="50"/> &nbsp; <img src="img/icons/perception.png" title="Perception" width="50"/> &nbsp; <img src="img/icons/see.png" title="See" width="50"/>&nbsp; <img src="img/icons/feel.png" title="Feel" width="50"/> &nbsp; <img src="img/icons/motion.png" title="Motion" width="50"/>

<br>

{% include style-barImpl.html %}


<br>

{% include pie_chartImplicationHow.html %}

<br>

<h1> Positive or Negative Emotional Analysis All Tweets </h1>
<br>

<img src="img/icons/negemo.png" title="Negative Emotion" width="50"/> &nbsp; <img src="img/icons/sad.png" title="Sadness" width="50"/> &nbsp; <img src="img/icons/negate.png" title="Negation" width="50"/> &nbsp; <img src="img/icons/anxiety.png" title="Anxiety" width="50"/> &nbsp; <img src="img/icons/swear.png" title="Swearing" width="50"/> &nbsp; <img src="img/icons/anger.png" title="Anger" width="50"/> &nbsp; <img src="img/icons/posemo.png" title="Positive Emotion" width="50"/> &nbsp; <img src="img/icons/achiev.png" title="Achievement" width="50"/> &nbsp; <img src="img/icons/assent.png" title="Assent" width="50"/>

<br>

{% include basic-barEmotions.html %}

<br>

<h1> Sentimental Analysis for Gender </h1>
<br>

{% include bar_pyramidGender.html %}

<br>

<h1> Sentimental Analysis over Time </h1>

<h1> Context & Thematics </h1>
<br>

{% include TimeSentimental2.html %}

<br>

<h1> Emotions & Implications </h1>
<br>

{% include TimeSentimental1.html %}

<br>

</center>






