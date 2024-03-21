---
title: Water quality in Canada
date: 2023-06-05
---
<h2> How clean is Canada’s water? What the data shows</h2>

<p>Grades 9 - 12</p>
<p>Water quality can have a tremendous impact on every life form — from microorganisms, to wildlife, livestock, and humans — as well as on terrestrial ecosystems, climate, and nature.</p>
<p>Statistics Canada collects water quality data from different aquatic ecosystems across the country. It monitors the various physical-chemical characteristics of our water, including pH, temperature, metal content, chemical species, alkalinity, and nutrients. Changes in each of these parameters can significantly affect ecosystems and societies.</p>
<p>How can we use observational data from <a href="https://data.ec.gc.ca/data/substances/monitor/national-long-term-water-quality-monitoring-data/" target="_blank" rel="noopener">Statistics Canada</a> to investigate the water quality in Canada? Are there any interesting trends in the above-mentioned quality parameters?</p>
<h4>To answer our question we:</h4>
<ul>
<li style="font-weight: 400;" aria-level="1">Used national long-term water quality monitoring data from <a href="https://data.ec.gc.ca/data/substances/monitor/national-long-term-water-quality-monitoring-data/" target="_blank" rel="noopener">Statistics Canada</a></li>
<li style="font-weight: 400;" aria-level="1">Created a series of <a href="https://en.wikipedia.org/wiki/Line_graph" target="_blank" rel="noopener">line graphs</a> and <a href="https://en.wikipedia.org/wiki/Scatter_plot" target="_blank" rel="noopener">scatter plots</a></li>
</ul>
<p><strong>Visualizing the data</strong></p>
<p>We investigated five parameters in the dataset – pH, dissolved oxygen, water temperature, dissolved sulphate, and dissolved phosphorus.</p>
<p><a href="https://en.wikipedia.org/wiki/PH" target="_blank" rel="noopener">pH</a> is a measure of the concentration of hydrogen ions in a solution. It indicates how <a href="https://en.wikipedia.org/wiki/Acid" target="_blank" rel="noopener">acidic</a> or <a href="https://en.wikipedia.org/wiki/Base_(chemistry)" target="_blank" rel="noopener">basic</a> the solution is — the higher the concentration of hydrogen ions, the more acidic the solution is. Even a slight change in the pH levels of water can have a drastic impact on the survival of aquatic life.</p>
<p>Dissolved oxygen is used by aquatic life for respiration. Low levels of dissolved oxygen can lead to increased mortality of fish eggs and negatively impact other aspects of aquatic ecosystems.</p>
<p>Changes in water temperature have wide-ranging impacts, including on the migration and breeding patterns of different species, the amount of dissolved oxygen, nutrient circulation, fish population, and so on.</p>
<p>Sulphate — an oxidized form of the element sulphur — is essential for many biological processes, and phosphorus is essential for the growth of plants and animals. Changes in sulphate and phosphate concentrations can seriously threaten ecological balance.</p>
<p>To investigate provincial trends in these water quality parameters, we created a series of line graphs. To take a closer look at a specific parameter, click the drop-down arrow at the top of the graph.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-files/data-viz-of-the-week/water-quality/visualizations/line_fig2.html" width="100%" height="500 " scrolling="no" seamless="seamless"></iframe></p>
<p>In the plot above, pH and concentrations of dissolved oxygen, sulphate, and phosphate appear to have remained consistent in all provinces, with minor yearly fluctuations. However, Manitoba showed an overall higher concentration of dissolved phosphorus. Nova Scotia’s water is low in pH, making it relatively acidic. In Alberta, British, Columbia, Manitoba, Yukon, and Prince Edward Island, the water is more basic, with high pH values.</p>

<p>Next, we created scatter plots to investigate dissolved oxygen in different provinces. The size of the bubbles represents the concentration of oxygen in the water; the larger the size, the higher the concentration.</p>
<p>In this interactive plot, you can toggle the province and territory names to turn on/off their respective data graphs. To take a closer look at a specific year, drag the button on the sliding bar at the bottom of the graph. To see an animation over the years, click the play button at the bottom of the graph.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-files/data-viz-of-the-week/water-quality/visualizations/oxygen_dissolved_mapped.html" width="100%" height="800" scrolling="no" seamless="seamless"></iframe></p>
<p>The scatter plot allows us to look at specific locations by latitude and longitude. You can observe the same trends as the line graph, with no significant changes in the overall concentration of dissolved oxygen. You can also see that more observations are made in BC than in any other province.</p>
<p>While creating the above visualizations, we came across some strange values, where measurements deviated from the general patterns. Tackling outliers like these in data is a common and important element of data science. Take a look at the <a href="https://hub.callysto.ca/jupyter/hub/user-redirect/git-pull?repo=https://github.com/callysto/data-viz-of-the-week&amp;branch=main&amp;urlpath=notebooks/data-viz-of-the-week/water-quality/water-quality.ipynb&amp;depth=1" target="_blank" rel="noopener">Jupyter Notebook</a> to learn how we tackled the outliers in these datasets.</p>
<p>What do you notice in this data visualization? What makes the water in Nova Scotia more acidic? What is the best type of graph to show the quality of Canadian water? Which additional parameters would you investigate to discover more about the water quality?</p>

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
<p>Go to our <a href="https://hub.callysto.ca/jupyter/hub/user-redirect/git-pull?repo=https://github.com/callysto/data-viz-of-the-week&amp;branch=main&amp;urlpath=notebooks/data-viz-of-the-week/water-quality/water-quality.ipynb&amp;depth=1" target="_blank" rel="noopener">walk-through</a> (in Jupyter notebook format) to see how the data science process was applied to create these graphs, from formulating a question, to gathering the data, and analyzing the data with code.</p>