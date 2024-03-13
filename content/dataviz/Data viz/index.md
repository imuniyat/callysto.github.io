---
title: Data visualizations
date: 2024-02-26
---
These pre-made, introductory data science lessons are a way for students to develop critical thinking and problem solving skills. We start with a question, find an open dataset to answer the question, and then ask students to reflect.

<a href="./HTML/test.html" target="_blank">Test page</a>
<!-- <a href="./content_1.md" target="_blank">Test md</a> -->
hello world
<a href="/workspaces/callysto.github.io/content/post/content_1.md" target="_blank">Test md</a>




{{< spoiler text="Understanding stock market" >}}
<p>Grades 9 - 12</p>
<p>Grasping financial literacy through stocks from a young age establishes a foundation for long-term financial literacy, encouraging students to make informed decisions, develop saving habits, and leverage the compounding benefits of early investments.</p>
<p>In this data visualization, our goal is to introduce the concept of stocks, highlighting the advantages of cultivating a positive mentality and mindset towards investing.</p>
<p><strong>To answer our question we used data from:<br>
</strong></p>
<ul>
<li>Python library <a href="https://pypi.org/project/yfinance/" target="_blank" rel="noopener">yfinance</a></li>
<li><a href="https://www.nasdaq.com/market-activity/stocks/screener" target="_blank" rel="noopener">Nasdaq</a></li>
</ul>
<p>Yfinance is a Python library which helps to download market data using Yahoo!’s finance API. With this library, we can freely find historical data about stocks in the stock market.</p>
<p><strong>Visualizing the data</strong></p>
<p>Initially, we explored the opening and closing price history of the S&amp;P 500 Index — a collection of 500 of the biggest companies in the United States, chosen to show how well the stock market is doing overall. It helps investors understand if the stock market is going up or down.</p>
<p>&nbsp;</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-files/data-viz-of-the-week/privacy-policy-readability/readability.html" width="100%" height="500 " scrolling="no" seamless="seamless"></iframe></p>
<p>The trend line doesn’t show a significant increase until approximately 1990. Following this period, we observe a gradual uptick in stock prices, punctuated by periods of substantial growth (such as in the 2010s) and stagnation (as seen in the 2000s). However, the overall trend indicates an upward trajectory, despite periods of sudden growth and decline. This analysis served as a good benchmark to demonstrate how investing in a safe group of stocks like an ETF can lead to long-term growth and financial sustainability.</p>

<p>Afterwards, we implemented the ability for users to research the historical price of different stocks on the Nasdaq, leading to informative insights such as which stocks historically perform better during particular periods and analyzing patterns of when prices generally will rise or fall.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-files/data-viz-of-the-week/stock-prices/AAPL.html" width="100%" width="100%" height="700" scrolling="no" seamless="seamless"></iframe></p>
<p>In this particular example, we can see Apple’s historical stock prices from 2000 to 2023. Apple’s peak stock price was around 2021 to 2022, and throughout Apple’s history, its stock price has generally shown a slow increase, starting from approximately 2010 onwards.</p>

<h2><b>Reflect on what you see</b></h2>
<p>Look and interact with the data visualization above. When you hover the mouse over the bar graph, you’ll notice more information appears.</p>
<p><strong>Think about the following questions.</strong></p>
<ul>
<li>What do you notice about the visualizations?</li>
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
<h2>Learn how we visualized the data</h2>
<p>Go to our <a href="https://hub.callysto.ca/jupyter/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fcallysto%2Fdata-viz-of-the-week&amp;branch=main&amp;subPath=stock-prices/stock-prices.ipynb&amp;depth=1" target="_blank" rel="noopener">walk-through</a> and <a href="https://hub.callysto.ca/jupyter/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fcallysto%2Fdata-viz-of-the-week&amp;branch=main&amp;subPath=stock-prices/stock-prices-ML.ipynb&amp;depth=1" target="_blank" rel="noopener">Machine Learning notebook walk-through</a> (in Jupyter notebook format) to see how the data science process was applied to create these graphs, from formulating a question to gathering the data and analyzing the data with code.</p>

{{< /spoiler >}}
