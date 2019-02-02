---
layout: post
title: "GDP and unemployment in India"
author: Vikas Dhiman
---

Unemployment is in news again, as it should be. The unemployment rate according to a leaked NSSO report is [6.1%][bs2019Jan30nsso]. Another source, CMIE, puts the number at [7.13%][cmie2019Feb01].
To put them in context, unemployment rate did not reach more than
[4.5%][te2019ind] in the last 25 years. China has an unemployment rate of [3.8%][te2019china] and OECD average is [5.2%][oecdunemp].

Current establishment has been trying to hide unemployment figures and in fact
denying the existence of high unemployment figures. One common defense the
government and its spokespersons have employed is the prevalence of high GDP.
Let investigate the weight of that argument. You can watch [Arun
Jaitley][jaitley2019video] and [Rajiv Kumar][kumar2019video] making that claim
independently (or presumably so).

# Okun's law and its reliability

What is the relationship between unemployment and GDP? A quick search points me
to [Okun's Law][okuns2018May22okuns], which provides a correlation between GDP
growth and unemployment of the form:

> Change in the unemployment rate = α + β×(Real output growth)

where b is called the _Okuns coefficient_ usually negative and within the range
of -0.1 to -0.7. Here's Okun's coefficient for G7 economies (forecasted vs data)
from an [IMF working paper][ball2014forecasters]

![Variation in Okun's coefficient in G7 countries](/assets/media/20190202_003326_D8g21f.png)

Using data from 1948 and 1960, "which would have have been available to Okun",
[Knotek][kansascityfed.org] estimates b = -0.7 and a = 0.30. However, [Wikipedia
page][okunwiki20190201] on Okun's "law" clarifies it as being "rule of thumb".
An [IMF working paper][ball2014forecasters] begins by describing the history of
Okun's "law":

> Okun (1962) reported a negative short-run correlation between unemployment
> and output that has become known as Okun's law and is a stable of
> macroeconomic textbooks.
   
Although a "staple of textbooks", there is only a weak correlation between GDP
increase and employment increase is evident from the plot (from Wikipedia) that
defines the correlation:

![Okun's law data. Source: Wikipedia](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b3/Okun%27s_Law_2016.svg/300px-Okun%27s_Law_2016.svg.png){:standalone}


Having said that Okun's "law" as a broad trend generally holds with broad
aberrations and variations as usual with many macroeconomic indicators. The IMF
report finds and concludes that "professional forecasters believe in Okun's law
to a degree merited by how well it holds in the data". It quotes [Mitchell and
Peace (2010)][MitchellAndPeace2010], who found that the "predictions of
unemployment and real growth move in opposite directions, as per Okun's Law"
with correlation of 0.6 in the data. Another [review][frbsf.org] shows that
apparent aberration Okun's law in the 2008 US recession does not hold with
subsequent revisions to the GDP data.

# Is high Unemployment rate with high GDP growth possible?

Arun Jaitley referred to unemployment rate along with high GDP growth as
"economic absurdity". To be honest his words were "it will be an economic
absurdity to say that such a high econmic growth ... does not lead to creation
of jobs". However, no one is arguing that creation of jobs is not happening.
The real question is whether the net job creation is more than the relevant
population growth. The unemployment rate captures that.

So given the Okun's "law", is high unemployment rate with high GDP growth
possible. Let us see if that has happened before. Here's a scatter plot from USA
data:

<style>
figure > img { width: 80%; margin:auto; } 
figure > figcaption { text-align: center; }
</style>

![The difference version of Okun's law, quarterly. Source: kansascityfed.org](/assets/media/okuns-law-outliers.png){:standalone}

Pay attentions to the points where real GDP growth is around 7% and unemployment rate is
still increasing? There are around 4 points that satisfy this criterion.

But this is a very small drop unemployment rate per quarter. The worst outlier
is 0.25% unemployment growth for 7% GDP growth. And there are only 4 such
outliers from a data of 240 data points, which points to a probability of less
than 0.014.

To summarize this means that it is highly unlikely that unemployment increases
with increase in GDP. Even when it increases, it increases by small percentage
points. However, [CMIE][cmie2019Feb01] unemployment data for the past 1.5 years
(6 quaters) shows that unemployment increased for two quarters from [3.2% to
7.3%][cmie2019Feb01], while the GDP has grown at the annual rates varying from
[5.6% to 8.2%][te2019indGDP].

![CMIE unemployment data](/assets/media/20190202_013450_oDniZ7.png){:standalone}

<figure>
<iframe src='https://tradingeconomics.com/embed/?s=ingdpy&v=201901311346a1&h=300&w=600&ref=/india/gdp-growth-annual' height='300' width='600'  frameborder='0' scrolling='no'></iframe>
<figcaption>
GDP annual GDP data. Source: <a href='https://tradingeconomics.com/india/gdp-growth-annual'>tradingeconomics.com</a>
</figcaption>
</figure>

# Jobless growth in South Africa and South Asia?

The curious thing about Okun's law is that most of the data comes from developed
countries like USA and G7. Does the law even hold in developing countries? A
quick search on jobless growth leads to many studies about South Africa and
India that point to jobless growth. The usual justification is that the
economies are going through "structural" changes. But before we dive into the
jobless growth topic in detail we must recognize that even in developed
economies the Okun's coefficient has undergone sweeping shifts. For example, in 
USA Okun's coefficient has increased from -0.7 to -0.4 with a rapid shift in 1995.

![Rolling regression estimates](/assets/media/20190202_022312_l2Phs3.png){:standalone}

## Jobless manufacturing growth in Indian 1980-90 version

There is consensus among scholars that Indian manufacturing sector showed a
period of jobless growth of 8.66% with an annual employment growth of
[0.53%][indiaenvironmentalportal.org.in]. The problem of jobless growth is being
discussed in [epw.in][epw-engage] since 2015.

# References

[okuns2018May22okuns]: https://web.archive.org/web/20190201/https://www.investopedia.com/articles/economics/12/okuns-law.asp
* [1][okuns2018May22okuns]
Okun's Law: Economic Growth And Unemployment. Ryan Furhmann. May 22, 2018. On Investopedia

[jaitley2019video]: https://www.youtube.com/watch?v=iWFtNlklOg8?t=32
* [2][jaitley2019video] Arun Jaitley's statement

[kumar2019video]: https://www.youtube.com/watch?v=qF7c1txemUc
* [3][kumar2019video] Niti Aayog press conference

[editorial2019Jan30livemint]: https://www.livemint.com/opinion/online-views/unwilling-to-face-an-inconvenient-truth-1548866799792.html
* [4][editorial2019Jan30livemint] Unwilling to face an inconvenient truth. Livemint editorial. Accessed 2019 Feb 01.

[te2019china]: https://web.archive.org/web/20190201/https://tradingeconomics.com/china/unemployment-rate
* [5][te2019china] Trading Economics data on Chinese unemployment. Accessed 2019 Feb 01.

[te2019ind]: https://web.archive.org/web/20190201/https://tradingeconomics.com/india/unemployment-rate
* [6][te2019ind] Trading Economics data on Indian unemployment. Accessed 2019 Feb 01.

[bs2019Jan30nsso]: https://www.business-standard.com/article/economy-policy/unemployment-rate-at-five-decade-high-of-6-1-in-2017-18-nsso-survey-119013100053_1.html
* [7][bs2019Jan30nsso] Unemployment rate rose to a 45-year high of 6.1%, as per the NSSO's annual household survey of 2017-18 - the first one after demonetisation. Somesh Jha. 2019 Jan 31.

[cmie2019Feb01]: https://web.archive.org/web/20190201/https://unemploymentinindia.cmie.com/
* [8][cmie2019Feb01] CMIE Unemployment data. Accessed 2019 Feb 01.

[okunwiki20190201]: https://en.wikipedia.org/w/index.php?title=Okun%27s_law&oldid=878508266
* [9][okunwiki20190201] Wikipedia Okun's law. Accessed 2019 Feb 01.

[MitchellAndPeace2010]: http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=6C099A940FFAF11913B5BE58498073C9?doi=10.1.1.691.5877&rep=rep1&type=pdf
* [10][MitchellAndPeace2010] Mitchell and Peace (2010) Do Wall Street economists believe in Okun's Law
and the Taylor Rule?

[ball2014forecasters]: https://www.imf.org/external/pubs/ft/wp/2014/wp1424.pdf
* [11][ball2014forecasters] IMF Working report: Do Forecasters Believe in Okun’s Law? An Assessment of Unemployment and Output Forecasts. Laurence Ball, João Tovar Jalles, and Prakash Loungani. 2014

[oecdunemp]: https://web.archive.org/web/20190201/https://data.oecd.org/unemp/unemployment-rate.htm
* [12][oecdunemp] OECD unemployment average. Accessed 2019 Feb 01

[frbsf.org]: https://www.frbsf.org/economic-research/publications/economic-letter/2014/april/okun-law-deviation-unemployment-recession/
* [13][frbsf.org] Interpreting Deviations from Okun’s Law. Mary C. Daly, John Fernald, Òscar Jordà, and Fernanda Nechio. 2014

[kansascityfed.org]: https://www.kansascityfed.org/Publicat/ECONREV/PDF/4q07Knotek.pdf
* [14][kansascityfed.org] How Useful is Okun's Law? By Edward S Knotek II

[te2019indGDP]: https://web.archive.org/web/20190201/https://tradingeconomics.com/india/gdp-growth-annual
* [15][te2019indGDP] Trading economics GDP data for India. Accessed 2019 Feb 01

[indiaenvironmentalportal.org.in]: http://www.indiaenvironmentportal.org.in/files/Growth%20sans%20Employment.pdf
* [16][indiaenvironmentportal.org.in] Growth sans employment: a Quarter century of Jobless Growth in india’s Organised Manufacturing. KP Kannan, G Raveendran.

[epw-engage]: https://www.epw.in/engage/article/unemployment-jobs-growth-india
* [17][epw-engage] The Unemployment Paradox: Looking at Growth Without Jobs. By EPW Engage. Accessed 2019 Feb 01.
