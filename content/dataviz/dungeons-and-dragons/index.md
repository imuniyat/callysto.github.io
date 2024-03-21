---
title: How to create the best Dungeons & Dragons character
date: 2023-04-18
---
<h2>From Paladins to Warlocks: which Dungeons & Dragons class will rule them all?</h2>

<p><b>Grades 9 - 12</b></p>
<p>Dungeons &amp; Dragons (DnD) has been enchanting players with its immersive roleplaying experience since 1974. The game has influenced everything from comics to the latest Dungeons &amp; Dragons movie, which was released in April 2023. With more people than ever starting to play DnD, let's take a closer look at the most sought-after qualities to have in a character, using data science.</p>
<p>What are the most popular races and classes (a character’s occupation or vocation) among DnD players? Can data science unlock the secret to building a formidable character?</p>
<h4>To answer our question we:</h4>
<p>Used data from a GitHub user who created an app for printing DnD character sheets. The app also collects data on the characters, and the user compiled it into a comprehensive dataset that is available on <a href="https://github.com/oganm/dnddata" target="_blank" rel="noopener">GitHub</a>.</p>
<p><strong>Visualizing the data</strong></p>
<p>In DnD, players take on the roles of adventurers who battle fearsome foes and overcome challenges, all while following a story crafted by a skilled Dungeon Master (DM). Players create and control a unique character from a variety of classes and/or races, each with their own strengths, weaknesses, and personalities.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-files/data-viz-of-the-week//dungeons-dragons/img/classes.html" width="100%" height="500 " scrolling="no" seamless="seamless"></iframe></p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-files/data-viz-of-the-week//dungeons-dragons/img/races.html" width="100%" height="500 " scrolling="no" seamless="seamless"></iframe></p>
<p>In the above visualization, we've plotted the most popular classes chosen by players in our dataset, along with their frequency of selection. The Fighter class stands out as the most commonly chosen one, closely followed by Rogue and Cleric. Hover your mouse over the plot to see the exact number of times each class was chosen.</p>
<p>In the second graph, we explored the most popular DnD races. As it turns out, Humans are the most frequently chosen race of all when it comes to character creation.</p>

<p>Next, we looked at the most popular combination of races and classes in our dataset. The largest number of players chose a combination of the Human race and Fighter class, followed by Human/Cleric, and Human/Rogue.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-files/data-viz-of-the-week//dungeons-dragons/img/heatmap2.html" width="100%" height="700" scrolling="no" seamless="seamless"></iframe></p>
<p>The choice of races and classes determines a character’s abilities and how they interact with the world. In the next plot, we examined the distribution of strength (STR) ability among different race/class combinations.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-files/data-viz-of-the-week//dungeons-dragons/img/abilities.html" width="100%" height="800" scrolling="no" seamless="seamless"></iframe></p>
<p>In this interactive plot, you can toggle class names and view their respective data. When comparing race/class combinations with the Fighter class, for example, we notice that Human/Fighter has a lower strength ability score than Orc/Fighter or Minotaur/Fighter. Check out our Dungeons &amp; Dragons <a href="https://hub.callysto.ca/jupyter/hub/user-redirect/git-pull?repo=https://github.com/callysto/data-viz-of-the-week&amp;branch=main&amp;urlpath=notebooks/data-viz-of-the-week/dungeons-dragons/dungeons-and-dragons.ipynb&amp;depth=1" target="_blank" rel="noopener">Jupyter Notebook</a> for similar plots on all six ability scores used in DnD. It also includes a section on using data science for character creation.</p>
<p>Whether you are a seasoned player or just starting out, this data may surprise you and guide you to create your next character.</p>

<h2><b>Reflect on what you see</b></h2>
<p>Look and interact with the data visualizations above. When you hover your mouse over the plots, you’ll notice more information appears. You can also use the legend to make plots appear and disappear.</p>
<p><strong>Think about the following questions.</strong></p>
<ul>
<li>What do you notice about these graphs?</li>
<li>What do you wonder about the data?</li>
</ul>
<h4><b>Use the fill-in-the-blank prompts to summarize your thoughts.</b></h4>
<ul>
<li aria-level="1">“I used to think _______”</li>
<li aria-level="1">“Now I think _______”</li>
<li aria-level="1">“I wish I knew more about _______”</li>
<li aria-level="1">“These data visualizations remind me of _______”</li>
<li aria-level="1">"I really like _______”</li>
</ul>
<h2><b>Learn how we visualized the data</b></h2>
<p>Go to our <a href="https://hub.callysto.ca/jupyter/hub/user-redirect/git-pull?repo=https://github.com/callysto/data-viz-of-the-week&amp;branch=main&amp;urlpath=notebooks/data-viz-of-the-week/dungeons-dragons/dungeons-and-dragons.ipynb&amp;depth=1" target="_blank" rel="noopener">walk-through</a> (in Jupyter notebook format) to see how the data science process was applied to create these graphs, from formulating a question to gathering the data and analyzing the data with code.</p>