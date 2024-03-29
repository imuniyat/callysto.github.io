---
title: Data visualizations
date: 2024-02-26
---
These pre-made, introductory data science lessons are a way for students to develop critical thinking and problem solving skills. We start with a question, find an open dataset to answer the question, and then ask students to reflect.

<a href="./HTML/test.html" target="_blank">Test page</a>
<!-- <a href="./content_1.md" target="_blank">Test md</a> -->
hello world
<a href="/workspaces/callysto.github.io/content/post/content_1.md" target="_blank">Test md</a>




{{< spoiler text="Exploring Government funding allocations" >}}
<p>Grades 6 - 9</p>
<p>Understanding the Canadian government's budget, expenditures, and future spending plans is important for promoting transparency and accountability. Moreover, it allows us to pinpoint areas for optimization, focusing on high-spending sectors.</p>
<p>In this data visualization, we examined how various sectors within the Canadian government allocate their budgets. By identifying the highest and lowest spenders, we seek to understand the distribution of expenses and discover trends in budget allocation for crucial categories like health and defense.</p>

<p><strong>To answer our question we used data from:<br>
</strong></p>
<ul>
<li><a href="https://www.statcan.gc.ca/en/start" target="_blank" rel="noopener">Statistics Canada</a></li>
<li><a href="https://search.open.canada.ca/opendata/" target="_blank" rel="noopener">Open Government portal</a></li>
</ul>
<p><strong>Visualizing the data</strong></p>
<p>First, we created a stacked bar graph representing the general progression of government expenses between 2008 and 2021.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-files/data-viz-of-the-week/government-spending/stacked_categories.html" width="100%" height="500 " scrolling="no" seamless="seamless"></iframe></p>
<p>Analyzing the visualization provides valuable insights into the government's priorities. Categories like Social Protection and Health consistently stand out as top priorities, showing minimal fluctuations over the years. This pattern extends to other categories, indicating relatively stable trends. Yet, it's essential to note that even seemingly small changes can have significant impacts when viewed on a larger financial scale.</p>

<p>We can also visualize the changes in expense allocations for each category individually. The visualization below shows these changes, with green categories having increased in budget allocations and red categories having decreased in budget allocations.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-files/data-viz-of-the-week/government-spending/percentage_fig.html" width="100%" height="700" scrolling="no" seamless="seamless"></iframe></p>
<p>Half the categories saw a decrease in percentage, while the other half increased from 2008 to 2021. Notably, the largest jump occurred in 2019-2020, with a 7% increase in social protection, likely due to the onset of Covid-19. Interestingly, health, typically a priority in crises, saw a decrease.</p>
<p>Next, we used a Folium map to show the spending allocations of each province. In the following interactive visualization, you can navigate to the top tab labelled “Column”, choose the specific category of interest, and see the colours on the map. For each category, deeper shades of green indicate a higher allocation of government budget, while lighter hues suggest a comparatively lower allocation.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-files/data-viz-of-the-week/government-spending/folium_map.html" width="100%" height="400" scrolling="no" seamless="seamless"></iframe></p>

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
<p><a href="https://hub.callysto.ca/jupyter/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fcallysto%2Fdata-viz-of-the-week&amp;branch=main&amp;subPath=government-spending/government-spending.ipynb&amp;depth=1" target="_blank" rel="noopener">Go to our walk-through</a> (in Jupyter notebook format) to see how the data science process was applied to create these graphs, from formulating a question to gathering the data and analyzing the data with code.</p>
{{< /spoiler >}}


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
