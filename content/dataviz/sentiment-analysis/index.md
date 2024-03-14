---
title: YouTube’s most and least favourite coding languages
date: 2023-08-23
---
<h2>Which programming language is most favourably received among YouTubers?</h2>

<p><b>Grades 6 - 12</b></p>
<p>Natural Language Processing (NLP), a computer science and linguistics subfield, aims to help computers comprehend human languages.</p>
<p>Central to NLP is sentiment analysis: the process of figuring out whether a piece of text expresses positive, negative, or neutral feelings.</p>
<p>We gauged YouTubers' preferred coding language by performing a sentiment analysis on comments from the platform's top ten programming tutorial videos. The results of this analysis are visualized below.</p>
<h4>To answer our question we:</h4>
<ul>
<li>Collected data from YouTube API (<a href="https://developers.google.com/youtube/v3">YouTube API</a>)</li>
<li>Examined the top 10 most-watched tutorial videos on popular programming languages C, Java, and Python</li>
<li>Collected the top 300 comments from each video</li>
<li>Ran a sentiment analysis on these comments</li>
</ul>
<p><strong>Visualizing the data</strong></p>
<p>The radar graph below illustrates how YouTubers feel about C, Java, and Python, three of the most popular coding languages.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none; --darkreader-inline-border-top: initial; --darkreader-inline-border-right: initial; --darkreader-inline-border-bottom: initial; --darkreader-inline-border-left: initial;" src="https://callysto.github.io/data-files/data-viz-of-the-week/NLP-sentiment-analysis/visualizations/radar_figure.html" width="100%" height="600 " scrolling="no" seamless="seamless" data-darkreader-inline-border-top="" data-darkreader-inline-border-right="" data-darkreader-inline-border-bottom="" data-darkreader-inline-border-left=""></iframe></p>
<p>The graph shows that Python has the highest positive score, making it the most positively perceived programming language among YouTubers. Java is a close second, while C is notably less positively received than the other two.</p>

<p>Next we wanted to explore what it means to be 'positively perceived'. Are 'positively perceived' programming languages generally easier to pick up? To answer this question, we investigated the number of times the words "easy,” “difficult,” or “challenging” appeared in the collected comments.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none; --darkreader-inline-border-top: initial; --darkreader-inline-border-right: initial; --darkreader-inline-border-bottom: initial; --darkreader-inline-border-left: initial;" src="https://callysto.github.io/data-files/data-viz-of-the-week/NLP-sentiment-analysis/visualizations/bar_figure.html" width="100%" height="600 " scrolling="no" seamless="seamless" data-darkreader-inline-border-top="" data-darkreader-inline-border-right="" data-darkreader-inline-border-bottom="" data-darkreader-inline-border-left=""></iframe></p>
<p>The bar graph indicates that the term "easy" is most commonly associated with Python, while the words "difficult" or "challenging" are most commonly associated with C.</p>
<p>Based on these findings, we can presume that programming languages which are simpler to learn are likely to be viewed more positively by YouTubers.</p>

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
<p>Go to our <a href="https://bit.ly/nlp-dataviz" target="_blank" rel="noopener">walk-through</a> (in Jupyter notebook format) to see how the data science process was applied to create these graphs, from formulating a question to gathering the data and analyzing the data with code.</p>