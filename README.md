<p align="center">
<a href="https://github.com/javiladino"><img src = "http://javierladino.com/fr/wp-content/uploads/2022/03/cropped-cropped-logo_nuevo_portafolio_01_150.png" width = 100> </a>
</p>

# Visual analysis of the presidential speech in France with python

## Introduction
This project will be my first experimentation with Web scraping tools, where using Python language I intend to make a visual analysis of the most common words between the inauguration speeches of Presidents François Hollande (2012) and Emmanuel Macron (2022), these speeches were obtained from the official website https://www.vie-publique.fr/ .

We will use Python's BeatifulSoup dependency to extract the information of each speech in its specific url, and then we will use the Word_cloud package to convert it into a cloud of the most used words achieving our first data visualization.

Then, by means of the Matplotlib dependency, we will obtain a visualization of the top 10 most common words, achieving a visual comparison of each speech according to its text.

At the end, we will make a primary analysis of the results and the usefulness of the Web scraping tool and Python as a language for data processing and visualization towards knowledge.

## DATA
All the information used is published on the official portal of Public Life of the French government, its link is available to all and this use will be for academic purposes only.

For chronology, I chose President Macron's last investiture speech made on May 7, 2022 and President Hollande's investiture speech of May 15, 2012. (President Macron's interim re-election speech of May 14, 2017 was omitted)

Technically the project is implemented in Python on a JupyterLab notebook locally and all its files will be hosted on GitHub for consultation and updating.

## Word Clouds

Word Cloud is a technique with which we visualize text data in which the size of each word indicates its frequency or importance.
For this task, we will be using the python library called 'word_cloud' developed by <b>Andreas Mueller</b>. <a hreef="https://github.com/amueller/word_cloud/">Here</a> you can find the repository and learn more about it.
***
## Analysis of results

Inauguration speech of President François Hollande on May 15, 2012.

Top 10 words: France, need, Republic, all, trust, place, justice, democracy, French, country.

President Macron's investiture speech delivered on May 7, 2022.

Top 10 words: France, country, people, Republic, project, Act, time, mandate, continue, May.

## Conclusion

We can generate several hypotheses when performing this data visualization exercise, especially if we start from the fact that in 10 years of difference many events have occurred that have changed the presidential discourse, added to the explosion of information (and misinformation) generated in social networks and internet, to the security problems with terrorist attacks, to the problems and actions against climate change, to the social and economic crisis due to the forced displacement of immigrants around the world, to the Covid-19 pandemic and the fragility of the medical system, and then to close with a war between Ukraine and Russia with a nuclear threat that destabilizes all sectors of society.

2012 was an intense year in France, due to an election campaign tainted by terrorism and the return to power of the Socialists with many challenges and low popularity for François Hollande, while 2022 (still in progress) comes burdened with the results of all kinds left by the Covid-19 pandemic, added to the position of France (and the European Union) in the face of the armed conflict in Ukraine and Russia, where, after the re-election of Emmanuel Macron, a great responsibility falls on the country in the midst of the energy, social and social uncertainty that plagues the world.

We can notice that the common words between the two speeches are: France, Republic and Country, which are set as the basis of a presidential text that involves the whole Nation, its sense of belonging, pride and freedom, a feeling that above all is part of the French people throughout its territory.

For the 2012 speech, it is worth noting the equivalence of seven words in second place of use (Necessity, republic, all, trust, place, justice and democracy), trust being, in my opinion, the word that frames the axis of his message, first because after 17 years, socialism returns to power and then because it marks a difference between him and his predecessor, Nicolas Sarkozy, relying on the exercise of power with dignity and simplicity.

Now for 2022, Emmanuel Macron after defeating the far-right Marine Le Pen in the second round, used in his speech a language that involved projection, diplomacy and inclusion, where in my point of view are the words: Project and Act, which give shape to that future that is longed for by all French people, involving his followers and detractors to face the situation and continue with the development of the country despite the times that are lived in the midst of uncertainty.

We can conclude that using this type of tools such as Web Scraping in Python to facilitate the understanding of the presidential speech, helps us to visually identify patterns that are usually linked to the situation, but that also have a context interpreted by each one according to their personal position.

Needless to say, this is just my opinion and one more interpretation of the message that a president of a nation wants to convey when he takes power in front of millions of people.
***

## References

https://github.com/amueller/word_cloud/
https://www.vie-publique.fr/discours/202852-declaration-de-m-emmanuel-macron-president-de-la-republique-sur-les-p
https://www.vie-publique.fr/discours/285059-emmanuel-macron-07052022-investiture-president-de-la-republique
https://matplotlib.org/

This project is implemented following <a href="https://www.linkedin.com/in/novelo-luis/">Luis Novelo tutorial</a> that you can find in his <a href="https://github.com/PhinanceScientist">GitHub</a>, thanks to him and his courses in Platzi I am very motivated to never stop learning.
