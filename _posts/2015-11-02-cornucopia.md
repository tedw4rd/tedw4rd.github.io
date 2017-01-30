---
layout: post
title:  "Cornucopia"
excerpt: "A strategy game to teach the impact of climate change"
feature: assets/img/portfolio/cornucopia/Cornucopia7.png
preview: assets/img/portfolio/cornucopia/preview.png
project: true
portfolio: true
tag:
- portfolio
- games
- education
- unity
- design
comments: false
---

### With [Caitlyn Crites](http://www.caitlyncrites.com/), [Jordan Santell](http://www.jsantell.com/), and the California Academy of Sciences

##### October 2015 to February 2016

#### What platform is it on?  Can I play?
Cornucopia is a browser game.  It can be played on any computer or mobile device with Firefox or Chrome installed.  You can play it on the [California Academy of Sciences's website](http://www.calacademy.org/cornucopia). You can also play the original prototype [here](http://tedw4rd.github.io/climate-change-game/).

<figure>
	<a href="/assets/img/portfolio/cornucopia/Cornucopia1.png"><img src="/assets/img/portfolio/cornucopia/Cornucopia1.png"/></a>
	<figcaption></figcaption>
</figure>

#### What’s it for?  Who’s it for?
Cornucopia is designed to teach kids about the impact that agriculture has on local water supplies.  It was commissioned by the California Academy of Sciences to be part of their Flipside Science curriculum after the initial prototype won the 2015 Climate Game Jam at the Academy.  After its release in August of 2016, it was used in classrooms to help teachers demonstrate how our food choices affect the environment, and how technology can help reduce some of the negative effects.

<figure>
	<a href="/assets/img/portfolio/cornucopia/Cornucopia3.png"><img src="/assets/img/portfolio/cornucopia/Cornucopia3.png"/></a>
	<figcaption>Cornucopia players can also learn interesting facts about the most common crops in California</figcaption>
</figure>

#### How do I play?
In Cornucopia, players manage a plot of land and the surrounding water supply and grow food for a nearby city.  Players receive contracts with the city to supply it with fruits, vegetables, and protein in exchange for points.  After receiving a contract, players need to decide which crops are the best way to fulfill that contract, keeping in mind the limited amount of land, water, and time they have.

<figure>
	<a href="/assets/img/portfolio/cornucopia/Cornucopia4.png"><img src="/assets/img/portfolio/cornucopia/Cornucopia4.png"/></a>
	<figcaption>Later levels in Cornucopia demonstrate the benefits of modern farming techniques such as drip line irrigation</figcaption>
</figure>

#### Who worked on the game?
I designed the original prototype with my friends Caitlyn Crites and Jordan Santell at the 2015 Climate Game Jam.  The three of us worked to develop the full version with guidance from Rik Panganiban, Andrew Collins, and other educational experts from the California Academy of Sciences.

#### What did you do?
At the Climate Game Jam, I took the lead in designing and tuning the core game mechanics, while my teammates worked to make the code and art.  My goal for the original prototype was to help the player understand the link between population, agriculture, and water, and how changing climate conditions affect all three.  The game's internal resource system modeled (very roughly) the real world systems of agriculture and population growth.  As crops grew, they used water, which was replenished by rainfall that varied with the seasons and global climate.  Once crops were grown, they could be harvested for food, which kept the city healthy, so it too could grow.  As the city grew, its demand for food and water increased in order for it to stay healthy.  This long feedback loop was limited by the rate at which water could be replenished, and so eventually a smart player's city would reach a point of equilibrium.  Changes in the local climate would disturb that equilibrium, and the player would notice their population begin to decline as drought conditions set in.

<figure>
	<a href="/assets/img/portfolio/cornucopia/CornucopiaProto.png"><img src="/assets/img/portfolio/cornucopia/CornucopiaProto.png"/></a>
	<figcaption>A screenshot from the original prototype developed at the Climate Game Jam</figcaption>
</figure>

For the public release of Cornucopia, I rebuilt the core game from scratch in the Unity engine. Rebuilding Cornucopia in a proper game engine allowed Caitlyn and I to bring the game to an isometric grid, as we envisioned at the Climate Game Jam, as well as add some more "juicy" elements to the game, such as particle effects, animation, and sound. In addition to audio and visual upgrades, I updated the game's mechanics to better convey topics the Academy educators wanted to teach. 

Once such update removed the "city growth" mechanic, where players' water supply would drain faster as the nearby city grew. The Academy's curriculum was focused mostly on the impact of agriculture and individual food choices, and less on personal water usage. Therefore, requiring the player to consider population size (and by extension its personal water usage) seemed uneccessary and distracting. I removed that mechanic and the goal to grow your city size as much as possible. However, without the nearby city, the player had no motivation to plant crops and experiment with the crop-water system. Thus, I added the "order" mechanic, which required players to grow crops of different varieties in exchange for points. This created an incentive to plant crops. Adding a "round timer" mechanic created an incentive to experiment with different crop configurations. With limited time to complete as many orders as possible, players were forced to find the most time, space, and water efficient configurations of crops to complete various orders. Finally, making the game turn-based let players strategize, and consider their choices before committing to them.

<figure>
	<a href="/assets/img/portfolio/cornucopia/Cornucopia5.png"><img src="/assets/img/portfolio/cornucopia/Cornucopia5.png"/></a>
	<figcaption>Many of the games core mechanics were reworked for its public release to allow players to strategize and make better decisions about their water usage</figcaption>
</figure>

#### What happened to the game?
Cornucopia was released to the public in August of 2016. You can play it on the California Academy of Sciences website [here](http://www.calacademy.org/cornucopia)

<figure>
	<a href="/assets/img/portfolio/cornucopia/Cornucopia6.png"><img src="/assets/img/portfolio/cornucopia/Cornucopia6.png"/></a>
	<figcaption></figcaption>
</figure>