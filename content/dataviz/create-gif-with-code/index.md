---
title: Creating GIFs with code
date: 2023-05-10
---

<h2> How can you make a GIF using code? </h2>

<p><b>Grades 5 - 8</b></p>
<p>A GIF is essentially a collection of individual, successive images or snapshots, which are then “played” in sequence as frames in a movie. For graphing purposes, they can be used to show changes over time or to highlight specific aspects of a data set.</p>
<p>This week, we hope to inspire you with the following visualizations: a growing red circle on a blue background, and an animation that is more data-oriented.</p>
<p><img loading="lazy" decoding="async" class="size-medium aligncenter" src="box.gif" width="400" height="400"></p>
<p>&nbsp;</p>
<p><span style="font-family: system-ui, -apple-system, BlinkMacSystemFont, &#39;Segoe UI&#39;, Roboto, Oxygen, Ubuntu, Cantarell, &#39;Open Sans&#39;, &#39;Helvetica Neue&#39;, sans-serif;">Can we create a GIF within Python?</span></p>
<h4>To answer our question, here is the key Python code to create a GIF:</h4>
<pre><span style="font-weight: 400;"># A function definition in Python
def make_box_gif():</span>
<span style="font-weight: 400;">    frames = [ ]</span>
<span style="font-weight: 400;">    for num in range(11):</span>
<span style="font-weight: 400;">    frames.append(box(num))&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>
<span style="font-weight: 400;">    frame_one = frames[0]</span>
<span style="font-weight: 400;">    frame_one.save("box.gif",format="GIF",append_images=frames,
    save_all=True, duration=200, loop=0)
</span></pre>
<p>In the code above, we provide an example of Python code that creates a growing circle animation. The code draws each frame for the animation, then saves it in the “GIF” format, which can then be used in web pages, documents, or other apps.</p>
<p>The animation below shows the individual frames that were created one by one, on the left, then put together on the right as a single “movie.” This movie is essentially made up of a series of frames that run together to show a growing circle.</p>
<p><img loading="lazy" decoding="async" class="size-medium aligncenter" src="boxes.gif" width="600" height="600"></p>
<p>In the following GIF, we investigated the interest rates in Canada and visualized the trends in the 21st century.</p>
<p><img loading="lazy" decoding="async" class="size-medium aligncenter" src="interest_nice.gif" width="800" height="550"></p>
<p>To learn more about creating GIFs with Python check out our <a href="https://hub.callysto.ca/jupyter/hub/user-redirect/git-pull?repo=https://github.com/callysto/data-viz-of-the-week&amp;branch=main&amp;urlpath=notebooks/data-viz-of-the-week/making-gifs/making-gifs-for-data-science.ipynb" target="_blank" rel="noopener">Jupyter Notebook</a>.</p>

<h2><b>Reflect on what you see</b></h2>
<p>Look and examine the animation above.</p>
<p><strong>Think about the following questions.</strong></p>
<ul>
<li>How many frames do you see stacked on the left?</li>
<li>Can you count the same number of frames on the animated video on the right?</li>
<li>About how many frames per second appear in the animation?</li>
<li>How might you make the animation smoother, and less jerky?</li>
<li>In the Python code, can you find the loop that creates the frames?
<ul>
<li>How many frames are created in that loop?</li>
<li>What do you think the “append” function does?</li>
</ul>
</li>
<li>In the Python code, can you find the function that saves the GIF file?
<ul>
<li>What is the name of the file?</li>
<li>What do you think “duration=200” means? What time units are used here?</li>
</ul>
</li>
<li>How might you use this to create the mathematical plot in the example above?</li>
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
<p><a href="https://hub.callysto.ca/jupyter/hub/user-redirect/git-pull?repo=https://github.com/callysto/data-viz-of-the-week&amp;branch=main&amp;urlpath=notebooks/data-viz-of-the-week/making-gifs/making-gifs-for-data-science.ipynb&amp;depth=1" target="_blank" rel="noopener">Go to our walk-through</a> (in our Jupyter notebook) to see how we used the data science process (formulating a question, gathering the data, analyzing the data with code, and creating the visualizations) to create the line graph.</p>