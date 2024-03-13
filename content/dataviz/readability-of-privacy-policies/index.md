---
title: Readability of social media privacy policies
description: We explore the readability of privacy policies on popular social media sites.
date: 2023-12-21
---

<p><b>Grades 5 - 9</b></p>
<p>Ever find yourself swiftly clicking “I understand and agree?” to lengthy terms and conditions on a new service you've just signed up for? Many people do, given the often intricate language involved.</p>
<p>Just how tough is it to read these terms? Our data visualization explores the readability of privacy policies on popular social media sites.</p>
<p><strong>To answer our question:<br>
</strong></p>
<ul>
<li>We used the <a href="https://github.com/citp/privacy-policy-historical" target="_blank" rel="noopener">Princeton-Leuven Longitudinal Privacy Policy Dataset</a>, an archive of website policies that spans 20+ years and hosts over 1 million policies. We picked the policies from popular social media sites: TikTok, Twitter, Facebook, Instagram, YouTube, and Pinterest.</li>
<li>We analyzed the readability of the privacy policies by looking at their grade level score, reading score, and reading time.</li>
</ul>
<p><strong>Visualizing the data</strong></p>
<p>The visualization below shows different measures of readability of privacy policies for TikTok, Twitter, Facebook, Instagram, YouTube, and Pinterest. You can toggle between the reading time, readability score, and grade level to compare how each of these companies perform using these different measures to test readability difficulty level.</p>
<p><strong>Readability score:</strong> Measures how easy it is to read a document. We applied the <a href="https://en.wikipedia.org/wiki/Dale-Chall_readability_formula" target="_blank" rel="noopener">Dale-Chall readability formula</a>, which uses a list of 3,000 words that are easily understood by an average 4th-grade student in America. Any word outside of that list is considered difficult to comprehend. A score of 9.0-9.9 indicates you have to be a college student to understand the text. Text with a score of 4.9 or lower means it is understandable by an average 4th-grade student, or younger.</p>
<p><strong>Grade score:</strong> Indicates the number of years of education required to understand the text. We applied the <a href="https://en.wikipedia.org/wiki/Flesch%E2%80%93Kincaid_readability_tests#Flesch%E2%80%93Kincaid_grade_level" target="_blank" rel="noopener">Flesch-Kincaid grade level formula</a>, where a score of 5 means that a fifth grader will generally understand the text.</p>
<p><strong>Reading time:</strong> Measures the time it takes an average person to read the text. It assumes a reading pace of 14.69 milliseconds (one-thousandth of a second) per character.</p>
<p>We used the Textstat Python Library to calculate all scores. You can find more information about the library <a href="https://pypi.org/project/textstat/" target="_blank" rel="noopener">here</a>.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-files/data-viz-of-the-week/privacy-policy-readability/readability.html" width="100%" height="500 " scrolling="no" seamless="seamless"></iframe></p>
<p>The bar graphs show the privacy policies of social media platforms are overall difficult to read. The grade level score for TikTok, Twitter, Facebook, Instagram, and YouTube are all above 18, which means their privacy policies are as difficult to read as an academic paper. Pinterest’s readability score is 7.16 (understood by an average 9th or 10th-grade student) and TikTok’s is 8.64 (understood by an average 11th or 12th-grade student).</p>
<p>TikTok's policy is the quickest to read. With the lengthiest reading time, Twitter matches TikTok in reading score and grade level.</p>

<h2><b>Reflect on what you see</b></h2>
<p>Look and interact with the data visualization above. When you hover the mouse over the bar graph, you’ll notice more information appears. You can toggle between grade score, reading score, and reading time to compare the three measures.</p>
<p><strong>Think about the following questions.</strong></p>
<ul>
<li>What is the reading score of the different privacy policies?</li>
<li>What grade level is needed to understand the privacy policies?</li>
<li>Is there a privacy policy that is easier to read than the others, or are they all similar in difficulty?</li>
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
<p><a href="https://bit.ly/readability-privacy-policies-notebook" target="_blank" rel="noopener">Go to our walk-through</a> (in Jupyter notebook format) to see how the data science process was applied to create these graphs, from formulating a question to gathering the data and analyzing the data with code.</p>