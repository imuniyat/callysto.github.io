---
title: Sunsets and sunrises
date: 2023-08-03
---
<h2>Have you ever wondered how sunset, sunrise, and day lengths compare globally?</h2>

<p><b>Grades 5 - 9</b></p>
<p>This exercise visualizes the specific times at which the sun rises and sets in various geographical locations at different times of the year. These times vary depending on the rotation of the Earth on its axis, time zones, and changes in the Earth’s atmosphere.</p>
<h4>To answer our question we:</h4>
<ul>
<li>Utilized API data from this website <a href="https://sunrise-sunset.org/api" target="_blank" rel="noopener">https://sunrise-sunset.org/api</a></li>
<li>Compared sunset and sunrise visualizations based on inputted latitudes and longitudes</li>
</ul>
<p><strong>Visualizing the data</strong></p>
<p>We began by inputting Calgary’s latitude and longitude into the API to see the current sunset and sunrise times in the region. We then manipulated aspects of the outputted data to improve the clarity of the visualization. The API outputs data in the 12-hour format. For ease of visualization and to better capture the differences between times, we converted the data into the 24-hour format.. Moreover, the times obtained from the API were in Universal Time Coordinated (UTC), but for visualization purposes, it’s more convenient to display the times using local time zones. To address this issue, we created a function that converts UTC into local times. Thankfully, using an online time zone converter (<a href="https://www.timeanddate.com/worldclock/converter.html" target="_blank" rel="noopener">https://www.timeanddate.com/worldclock/converter.html</a>) made the process much easier.</p>
<p>After addressing these major issues, we could visualize our sunset, sunrise, and day-length values.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none; --darkreader-inline-border-top: initial; --darkreader-inline-border-right: initial; --darkreader-inline-border-bottom: initial; --darkreader-inline-border-left: initial;" src="https://callysto.github.io/data-files/data-viz-of-the-week/sunset-sunrise/sunrise-sunset.html" width="100%" height="600 " scrolling="no" seamless="seamless" data-darkreader-inline-border-top="" data-darkreader-inline-border-right="" data-darkreader-inline-border-bottom="" data-darkreader-inline-border-left=""></iframe></p>
<p>The visualization reveals that sunrise times steadily decrease while sunset times and day lengths steadily increase during Spring. This increase is the result of the Earth’s rotation on its axis. During the spring season, the Northern Hemisphere leans towards the sun, leading to more daylight hours. The opposite occurs in the fall and winter seasons. During these months, the Northern Hemisphere leans away from the sun, leading to fewer daylight hours.</p>

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
<p>Go to our <a href="https://bit.ly/sunset_sunrise" target="_blank" rel="noopener">walk-through</a> (in Jupyter notebook format) to see how the data science process was applied to create these graphs, from formulating a question to gathering the data and analyzing the data with code.</p>