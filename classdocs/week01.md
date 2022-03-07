---
layout: page
title: 01 Introductions
permalink: /01_Introductions/
---

## Assignment:

- Make a public documentation site
- Make a About Page and introduce yourself
- Answer the following questions:
    - What is Life? How would you define it, can you actually define it?
    - What is BioHacking? What does it mean for you?
    - Why are you interested in Bio?

## Make Public Documentation Site.

I made my public documentation site on Github Page. Here are the procedures of setting up github pages.

1: Fork the repository of [BioHackAcademy Documentation Site Template](https://github.com/BioHackAcademy/BHA_DocumentationSite) (based on Jekylle Static Site Generators). How to fork the repository? You can find the "fork" button on top-right.

![](../images/week01/1-1.png)

2: "Rename" the repository. You can change the repository name in "setting".

![](../images/week01/1-2.png)

3: Setting Up GitHub Page. You can setup Github page at "Page" Section. Set a branch that publish to the pages. Here, I chooed the master branch of the repository.

![](../images/week01/1-3.png)

4: Clone the repository into my Local Computer. Execute this command in my PC. You can copy the URL of repository from the button "Code".

```
git clone git@github.com:yskt0810/bha2022.git
```

5: Open the repository with the Editor (Here is the example of VS Code to open the repository).

![](../images/week01/1-5.png)

6: Open _config.yml file to change some configurations of the website. The important parts of changes are here. You can also ckeck whole settings [here](https://github.com/yskt0810/bha2022/blob/master/_config.yml).

```

# Name of your site (displayed in the header)
name: Yosuke Tsuchiya

# Short bio or description (displayed in the header)
description: BioHack Academy 2022 blog

~~~~~

# Your website URL (e.g. http://barryclark.github.io or http://www.barryclark.co)
# Used for Sitemap.xml and your RSS feed
url: http://yskt0810.github.io

# If you're hosting your site at a Project repository on GitHub pages 
# (http://yourusername.github.io/repository-name)
# and NOT your User repository (http://yourusername.github.io)
# then add in the baseurl here, like this: "/repository-name"
baseurl: "/bha2022"

```

7: Commit and Push to the remote repository with these command.

Here is the commands that you can use for pushing the repository

- git add
- git commit
- git push

8: Wait a few seconds.... Then you can see the webpage are published!

![](../images/week01/1-6.png)

You can check the publishing process in "Action".

![](../images/week01/1-7.png)


## Make About Page

Open "about.md" in the template. And write my bio and profile, then push it into the repository.

About me page is [here](../about.md)

## Answering Questions

**What is Life? How would you define it, can you actually define it?**

Here is the brainstorming pictures in Local Session at BioClub Tokyo.

![](../images/week01/brainstorming.jpg)

Life is something like misterious and miracle... I couldn't imagine we can hack "life". Life is in Japanese "生命" or "生物". Someone say it should defined that contains metabolism. At the same local session, we learned the Bio safe rule in our lab, and it also gave me some hints that define about life, that is "self-replciation", something like the one that implemete the function that make their own copy. And, Life is the one that separated from the outer world (environment) and the membrane. In other word, life is the one that have their inside world that works automounsly.

**What is BioHacking? What does it mean for you?**

Hacking is the word originally from compurter science. Hack is, in my opininon, action to reveal unrevealed, solve problems and create sometihg new things with using computer skills. Therefore, it is defined that "hacker build things" (cited from Eric Raymond's article "[How to Become A Hacker](http://www.catb.org/~esr/faqs/hacker-howto.html#what_is)"). 

Bio (or Biology) is the scientific study of life. It contains various kinds of fields (from fundamental mechanism of life to infomatic anayisis of cells, genetic engineering... and so on). Bio-Hacking would be the action to reveal unrevealed, solve problems and create something new with using recent Biological knowledge. 

Also, as hacking are grown in open culture and hackers buit Internet and made Linux Operating System in there, "Bio-Hack" is included the action by citizen in open community (as opposite side of closed laboratories in unviersities or companies). That means, for me, I can also join to bio-hack (or bio-hack community). I like the open-source software/hardware and it's community. It is the pleasure that the bio technology would be more opened and anyone could be access to that, and I am happy to join there.

**Why are you interested in Bio?**

Because, I want to know what could we do with bio-hacking (or DIY Bio technology). Bio Hacking and biology is totally new field for me. My knowledge for biology is stopped in Japan's high school classes. I just heared the possibility of genetix engineering or other topics of recent Biology, and I want to learn about it. 

Also, I am belonging the fab community (global fab lab network). I also want make my own knowledges and skills that make almost anything (as fab lab makes almost anything). 