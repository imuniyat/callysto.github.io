---
title: Costliest natural disasters
date: 2023-05-30
---

<h2> What have been the most expensive natural disasters in Canada’s history?</h2>

<p><b>Grades 5 - 9</b></p>
<p>The costs of natural disasters can go beyond the immediate damage they cause. They can have both long-lasting economic and social impacts on affected communities. Understanding the costs associated with such events can help us better prepare for and respond to future calamities.</p>
<p>This week's data visualization investigates the most expensive disasters in recent history.</p>
<h4>To answer our question we:</h4>
<p>Used publicly available data from <a href="https://www.publicsafety.gc.ca/cnt/rsrcs/cndn-dsstr-dtbs/index-en.aspx" target="_blank" rel="noopener">Public Safety Canada</a>.</p>
<p><strong>Visualizing the data</strong></p>
<p>First, we examined the total cost of all disasters in the dataset that fit a specific subtype, such as floods, wildfires, and winter storms. To ensure that costs from the past were comparable to current-day amounts, we “normalized” the total cost. This is because costs tend to go up over time due to various reasons (this is known as “inflation”). We normalized the costs to 2016, the latest year for which our data source had available cost information.</p>
<p>From the following graph, we can see that floods have had the greatest financial impact on Canadians. The total cost of all floods in this dataset was over $500 million.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none; --darkreader-inline-border-top: initial; --darkreader-inline-border-right: initial; --darkreader-inline-border-bottom: initial; --darkreader-inline-border-left: initial;" src="https://callysto.github.io/data-files/data-viz-of-the-week/costliest-disasters/visualizations/total-costs.html" width="100%" height="850 " scrolling="no" seamless="seamless" data-darkreader-inline-border-top="" data-darkreader-inline-border-right="" data-darkreader-inline-border-bottom="" data-darkreader-inline-border-left=""></iframe></p>
<p>Then, we examined the total insurance cost for each type of disaster to create the graph below. The Y axis shows the total insurance cost, and the X axis shows the types of disasters.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none; --darkreader-inline-border-top: initial; --darkreader-inline-border-right: initial; --darkreader-inline-border-bottom: initial; --darkreader-inline-border-left: initial;" src="https://callysto.github.io/data-files/data-viz-of-the-week/costliest-disasters/visualizations/insurance-payments.html" width="100%" height="850 " scrolling="no" seamless="seamless" data-darkreader-inline-border-top="" data-darkreader-inline-border-right="" data-darkreader-inline-border-bottom="" data-darkreader-inline-border-left=""></iframe></p>
<p>What do you notice about the two graphs?</p>

<p>Lastly, we generated a scatter plot to visualize the cost of each disaster event in the dataset. The colour of the dots represents different types of disasters. The X and Y axes represent time and cost, respectively.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none; --darkreader-inline-border-top: initial; --darkreader-inline-border-right: initial; --darkreader-inline-border-bottom: initial; --darkreader-inline-border-left: initial;" src="https://callysto.github.io/data-files/data-viz-of-the-week/costliest-disasters/visualizations/normalized-costs.html" width="100%" height="800" scrolling="no" seamless="seamless" data-darkreader-inline-border-top="" data-darkreader-inline-border-right="" data-darkreader-inline-border-bottom="" data-darkreader-inline-border-left=""></iframe></p>
<p>You can see that most of the disaster events were in the same range for cost, with some major outliers. Another group of dots represents disasters whose total costs were slightly higher. From this scatter plot, we can see a few dots that represent outlier events that had a much higher cost compared to the other events in the dataset. For example, the total normalized cost of a 1998 winter storm was over $300 million.</p>
<ul>
<li>What kind of costs do you think are associated with disasters?</li>
<li>What type of disasters were the most expensive events?</li>
<li>Have the most expensive events happened more recently?</li>
</ul>

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
<p>Go to our <a href="https://hub.callysto.ca/jupyter/hub/user-redirect/git-pull?repo=https://github.com/callysto/data-viz-of-the-week&amp;branch=main&amp;urlpath=notebooks/data-viz-of-the-week/costliest-disasters/costliest-natural-disasters.ipynb" target="_blank" rel="noopener">walk-through</a> (in Jupyter notebook format) to see how the data science process was applied to create these graphs, from formulating a question to gathering the data and analyzing the data with code.</p>