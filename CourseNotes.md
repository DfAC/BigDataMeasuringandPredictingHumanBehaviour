 Big Data: Measuring and Predicting Human Behaviour
 ============

Presenters

Tobias, Suzy, [Chanuki](http://www.thoughtsymmetry.com/),


# Week 1

University of Warwick [online course](https://www.futurelearn.com/courses/big-data).

* power of the data lays in the fact that history repeat itself
* insight into a data that you can access free
	* internet data
		* google
		* wikipedia

## Future trend index

* based on google trend data
* difficult to compare between languages
	* simplify to digits search - how often ppl look for previous year
* published in [Nature paper](http://www.nature.com/articles/srep00350)
* critique included:
	* people might not be googling previous years exclusively out of a lack of financial forecast but for sourcing previous academic journals or recent historical events which appeared in the news and are archived on the net, perhaps all done in reference to current research and news.
	* The future orientation index may be a good way to establish if people are planning ahead as this generally includes financial planning
	* Excluding countries with less than 5 million users may limit the results in the context of studying 'Global' internet use. I say this because we may be overlooking something important, growth in internet usage and therefore information gain. According to the World Internet Users Statistics (Nov 2015) Africa as a continent, which is totally excluded (with 330,965,359 users) has increased internet usage by 7,23%. I however understand as said in the paper that Google Trends does not provide information on some of these areas. This may be a limitation.

## What else can we do with the data?

* The opportunities to manipulate Google data to gather insights is verging on infinite. Small businesses can target a geographic or demographic & other criteria to a fine level of detail, managing small marketing spends for example to maximise growth or test & learn. Researching your customer base & gathering insight be it on regional or global level is so easy (more specifically for western culture) which hopefully means research & development can be more relevant & minimise the need for massive business fails due to lack of understanding (marketing, Bridget Credland Dey)
* How do you verify the raw information being drawn from to create data sets is correct, no matter where you are looking? Can we assure the information Google provide?
*  Google data could be useful to predict some trends in society, but related to human bahavior it is more reasonable to think over not about subjects people searching in web, but about purposes they are searching particularly this. From this point , predicting human behavior could become easier, because volume of purposes is definitely shorter than total volume of global search.
* we cannot have just one data source to base our work on. Google been the biggest search engine provider today doesn't mean it's the only one.
*  am interested in who might be left behind in analyses of big data. In future I expect everyone will be connected (wearable tech, the internet of things and all that) but at the moment there are many people whose behaviour cannot be examined through analysis of big data because e.g. they don't Google search the internet, they don't book holidays or do their banking online etc. In the UK and elsewhere, older people are presumably less likely to leave a digital data trail. While analysing big data would seem a useful approach to understanding some of the problems we must face as a society in dealing with an ageing population (e.g. how should be organise our towns and cities, where should services be), the behaviour of older people is likely to be difficult to capture because they are off the digital grid.
* We are at an unprecedented moment in history where human behavior generates ocean of data in which to tap. This is exciting and I am pretty sure there is a huge amount of value to be extracted from these seas, in all domains (energy, health, crime, etc.). Yet, as with any powerful tool, it is not necessarily the tool in itself which is useful or harmful but the way it is used. Big data has to be developed with a clear conscience of its possibilities and possible flaws. Not all correlations mean something. Is the data pool relevant? Is the interpretation of the data correct? Is past behavior always representative of future behavior? Predicting the future thanks to the past is highlighting trends and extrapolating them further, which can be useful, but then what about disruption ? And what about ethics in all this? Do we want for example to live in a world where insurance premiums could be adjusted thanks to IoT captors and big data, calculating your probability to get sick or die? How do we use this potential without ending up in Minority Report or 1984? I am not criticizing or against Big Data (which is already there anyway), just highlighting the need to be careful with it.


## City visibility

* data about
	* infrastructure
	* environment
	* ppl
* [poor vs well off areas visibility](http://urbanopticon.org/)

## Where to get data from

* Data can be obtained from [google][Google_Trends] and [Wikipedia][Wiki_stats]. For [example](https://www.google.co.uk/trends/explore#geo&cmpt=q&q=Economy+class+flight,+Business+class+flight,+low+cost+flight,+flight+accidents).

d:/tmp/Dropbox/Edu/other/BigDataMeasuringandPredictingHumanBehaviour/

# Week 2

* google provides additional filters as it has additional knowledge about searches
* Google Trends normalise search data - each data point is divided by the total searches of the geography and time range it represents, to compare relative popularity. The resulting numbers are then scaled to a range of 0 to 100.
* google is not the only search engine, it is one of the most popular one.

## nowcasting

* big data allows for  faster measurements of human behaviour
	* this removes delay with the standard methods, it might lead to problems yet, see google flu
* correlation examples
	* car part searches related to no of cars sold
	* googling about HK and visit to [HK from this specific country](http://people.ischool.berkeley.edu/~hal/Papers/2011/ptp.pdf)
* we can use existing pattern to predict future behavior
	* Data is gained quickly while other data gathering methods can be cumbersome as large scale dataset allows us to find more patters
	* for example [predict rankings of item following week](http://www.pnas.org/content/107/41/17486.long),	 as [Sharad Goel](https://5harad.com/#about) shown
* for business
	* predicting proper growth patterns
	* predicting customer behaviour
	* building [client model predictions](http://www.mediaco.co.nz/) or for [climate](http://www.climateprediction.net/)
	*
* there are also [limitations of this use](http://mio.sagepub.com/content/9/2059799115622763.full)

## mobile apps

* [motion sensors informations](https://www.youtube.com/watch?v=ARdxlMpCu4o&list=PLEMiIcsJKOBcQfE2kwFY9GU4WzZ0lvJNS&index=9) or other sensors its very easy to extract information about people
	* eye blinks depends on our activity
	* research on bipolar disorder
	* [lumo lift](http://www.lumobodytech.com/lumo-lift/)
* the same thing applies to smart cities - seeing how brain behaves, using smart candles,
* privacy is overated?
* can be used for [health](https://www.youtube.com/watch?v=ZPXCF5e1_HI)

# Week 3 - predicitng stock market

* rapid measurements allows for better decisions and better reactions
* its all about decisions

* Physics deal with fluctuations

## Effect of printed news on stock markets

* analysis corpus of FT 2008-12, looking at stock market 3 days before and 3 days after the mention
* there was correlation between interest in company news and its stock prices
* transaction volume, absolute return also correlate with stock prices
* day return did now show correlation

## Google data and trading

* [searches correlate with financial events](https://www.google.co.uk/trends/explore#geo&cmpt=q&q=+financial+crisis,+Lehman+Brothers)
* google provides weekly searches
* there was correlation between google searches and trading volume

### Trading strategy

Can we create a trading strategy based on this one? Author used financially related words from Google and created buying strategy based on this one.

* google trends are on weekly basis so they checked week on week change - this week vs average of 3 previous weeks
* if down they buy, if up they sell - we do it every week on Monday
* [publication](http://www.nature.com/articles/srep01684)
* fix and hold strategy would give you 16%, random strategies would give (-20;20)
* search for **culture** would give 5%, search for **debt** would give 326%


Using FT word search created even better strategy. What if we use multiple key words? Its will be noisy so we
* reduce dimensionality using [Latent Dietrich Allocation](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation)
* trained LDA model on wikipedia
* created groups of words
* found relevant [keyword groups](https://www.youtube.com/watch?v=b42k7IZ9DcI&list=PLEMiIcsJKOBcQfE2kwFY9GU4WzZ0lvJNS&index=12) which allows to determine stock movement as [described here](http://www.pnas.org/content/111/32/11600.abstract)
* [there are other researches in this area](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0073791)

### [Using Wiki](http://www.nature.com/articles/srep01801)

Article in Nature is discussing share trading of Dow Jones Industrial Average (DJIA) based on the average viewing (from <stats.grok.se>) and editing (from Revision history) of 30 DJIA listed companies Wikipedia English entities for period 10th December 2007 and 30th April 2012.

* changes calculated as diff from n week average
* week end on Sunday, trading occurs on Monday to avoid overlap
* estimation of value gained is $R = \sum ln (value_{week_n end}-value_{week_n start})$
* to compare they used random step strategy (run 10k times)
	* neglecting 104 transaction fees, it is possible to sell stock without owning it
	* distribution return is not normal so they used non-parametric test, two-tailed two-sample Wilcoxon rank-sum test, Bonferroni correction applied
* then a more general approach was used of 285 general economic concepts
	* resutls of edits are more normalised around 0
	* results of views are again right skewed but without so visible peak at 1.4
	* there seems to be not enough edit data (few k on total, most pages <50), so ignored for future analysis
* 1-10 weeks averages have been tested, R values differ and all are above > 0
* they compared traffic to other Wiki pages to make sure that change in volume is not due to some other phenomena
	* strategies based on non-financially related pages where the same as average random ones
* authors think that Wiki searches can provide proxy for information gathering when spending
	* humans are loss averse, so more research might indicate willingness to sell stock

* [another article](http://www.pnas.org/content/111/32/11600.full.pdf) on the same topic

## behaviour changes

Be careful with relaying on research findings.

* human behaviour changes
* with money at stake ppl might consider polluting or changing the signal, especially since paper has been published


# week 4 - fighting crime

What is it obvious? Understanding complex systems is never obvious/easy as patters are changing all the time. Understanding patterns can also be used for [targeted manipulation](http://www.bloomberg.com/news/articles/2015-05-20/the-10-hedge-fund-supercomputer-that-s-sweeping-wall-street). If a lot of ppl know about it, then behaviour pattern changes as well. There is always a need for adaptive algorithms.

How can we predict human behaviour then? Our predictions can affect the system (human behaviour) even removing the pattern. Yet a lot of our behaviour is driven by habits, so it is difficult to change them.

## predicting crimes

We can use human behaviour to predict crime hotspots  and creating predictive policing software. Toby Daves (Department of Civil, Environmental and Geomatic Engineering at University College London) [describe environmental criminology](https://www.youtube.com/watch?v=ppQfb4ltzMM&list=PLEMiIcsJKOBcQfE2kwFY9GU4WzZ0lvJNS&index=13).

* more visited placed, more crime
	* betweens links to create more central areas (busiest streets)
* discussion highlighted more sophisticated burgers [using social media approach](http://www.scoop.co.nz/stories/BU1510/S00056/burglars-using-social-media-to-target-victims.htm)
	* how much data delivered information has been available before? Using street smart local cops?
* [other papers
	* <http://datapop.wpengine.com/wp-content/uploads/2015/08/Crime-Hotspots-Big-Data-London.pdf>
	* <http://www.theguardian.com/cities/2014/jun/25/predicting-crime-lapd-los-angeles-police-data-analysis-algorithm-minority-report> and <https://www.youtube.com/watch?v=Su9H9QtyMmc>
	* <http://www.bbc.co.uk/guides/zqsg9qt>
	* <http://www.sciencedirect.com/science/article/pii/S2405918815000021>

## [predicting protests](https://www.youtube.com/watch?v=Zp2yqTHOamI&list=PLEMiIcsJKOBcQfE2kwFY9GU4WzZ0lvJNS&index=7)

Big data is magnet to get needle from haystack. We can predict future events by using [information available on the internet](https://www.youtube.com/watch?v=x7PK8BOfkH0&list=PLEMiIcsJKOBcQfE2kwFY9GU4WzZ0lvJNS&index=14).

* initial model was based on contingency (entropy increases)
	* a burst happens and a lot of ideas spread
* instead ppl attending the same virtual space to share information
	* nothing on the tweets
	* a lot of organisational Facebook pages
	* eventually a single idea get promoted and get motion



## [Conflicts and opinions in Wikipedia](https://www.youtube.com/watch?v=GhkmCvIbSc0&list=PLEMiIcsJKOBcQfE2kwFY9GU4WzZ0lvJNS&index=15)

Looking at history of changes of the Wiki pages we can map conflicts of opinions. They came up with measure of controversy for article - for example [Jesus](http://www.economist.com/blogs/graphicdetail/2013/08/daily-chart-1) is [very controversial](https://en.wikipedia.org/wiki/Wikipedia:List_of_controversial_issues) in any language. You can also geolocate those problems - seeing how global different languages are.

## summary of week 4

* we do not displace crime by reducing it in one area
	* there been a number of research project
* privacy is issue
* most datasets data does not gerenalise to population at large
	* we can correct for those biases
	* sometimes we just want quick data, then we can just simplify this


# week 6 - Health

Note that week 5 was study break only. Week 6 focus on Health.

* point of the nowcasting is to speed up a process that normally takes weeks and months

## spread of epidemics predictions

* we can create model using data how ppl commute
* [Bruno Gonçalves](http://www.bgoncalves.com/) [interview](https://www.youtube.com/watch?v=I5d4C_5XUZQ&index=6&list=PLEMiIcsJKOBcQfE2kwFY9GU4WzZ0lvJNS) discuss details and system
	* requirements
		* population density and location
		* how ppl travel
	* model can predict how epidemics spreads
		* <http://www.thestar.com/news/insight/2016/02/22/how-a-toronto-company-used-big-data-to-predict-the-spread-of-zika.html>
* we can also use this information to predict how ppl behaviour will change in future
	* <https://theconversation.com/heres-how-tweets-and-check-ins-can-be-used-to-spot-early-signs-of-gentrification-57620>
	* <http://www.theguardian.com/commentisfree/2016/mar/02/battle-of-hastings-gentrification-sussex-rents-affordable>
	* <http://www.theguardian.com/world/2015/aug/23/europe-rural-urban-migration-threat-countryside>
* predicting other things
	* [weather](http://news.microsoft.com/features/every-second-counts-for-businesses-that-depend-on-accuweather-to-save-lives-stock-supplies-stage-events/#sm.00001alxqeknjgepbrdo5p7g48yiy)



# week 7 - Happiness

* nowcasting allows to provide results quicker than official statistics and with better graduation
* we should allow for ppl behaviour changes over time on our model

## measuring happiness with mobile phones

* George [talk](https://www.youtube.com/watch?v=3wrBe74REz0&index=16&list=PLEMiIcsJKOBcQfE2kwFY9GU4WzZ0lvJNS)
* hedonic concept - your current feelings
* we can measure the same using Tweeter and Facebook
	* we can use this data to understand how happiness spreads
	* ppl are happier on Weekends and least happy on Tuesday
	* correlation with feeling and rain
	* there is also an evidence that this will [propagate through the network](http://www.pnas.org/content/111/24/8788.full)
* references
	* <http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0090315>
	* [we work harder when we are happy](https://www.sciencedaily.com/releases/2014/03/140320100942.htm)
	* [world happiness report](http://worldhappiness.report/ed/2016/)

## id users

* we can identify ppl characteristics [from their profiles](http://www.pnas.org/content/111/24/8788.full) as discussed by Thore Graepel.
	* gender, nationality , political views can be predicted
	* identify likes for specific attributes
	* user privacy can be an issue here
* we can also identify individuals using big data
	* we can [use location, 4 data points](http://science.sciencemag.org/content/347/6221/536.full?ijkey=4rZ2eFPUrlLGw&keytype=ref&siteid=sci)

## how ppl look for future

Following discussion from first week, we can check how ppl in different countries google for dates. Pattern will be independent of language, check [England](https://www.google.com/trends/explore#q=%222013,+2012,+2011,+2010,+2009%22&geo=GB) and [Japan](https://www.google.com/trends/explore#q=%222013,+2012,+2011,+2010,+2009%22&geo=JP) for example


# week 7 - Mobility

* how big data can help us measure where people are and where they are going, and how big data might help in disasters
* what about subjective variables that diff between ppl?
	* we can still id those at scale and id relationships between them
	* ppl differences introduce noise yet pattern emerge if we collect enough data
	* if there is no insesitve (like manipulating stock market) ppl will not false data
	* using social media platform creates problem as we only work on subset of data and it does vary from time to time

## using mobiles data

### counting crowds

Friderico Botta talk was presented in [BBC](https://www.youtube.com/watch?v=TY59bJIZs2s) and [published](http://rsos.royalsocietypublishing.org/content/2/5/150162) discussed use of mobile phone data & calls, as well as Twitter to count how many ppl are at the event. He used sample data for for Milano city centre and football stadium.
* data shown
	* volume of calls
	* data usage
	* geotagged tweets
* prediction using only one sorce is very reliable.  Adding more than one source does not improve the model.

### tracking ppl

Reserachers have used [dedicated app](https://www.youtube.com/watch?v=Z1BVS5Nkc_E) to estimate ppl movement during [Lord's Mayor Show 2011](https://vimeo.com/39184250). For user to use app there has be insensitive to use application

### predicting where ppl are going

Mirco [mined ppls positioning data](https://www.youtube.com/watch?v=Yi9wx7Raa_Y&index=19&list=PLEMiIcsJKOBcQfE2kwFY9GU4WzZ0lvJNS) showed how knowing social links of ppl create better model.


### hurracane Sandy with Flickr


As discussed in [paper](http://www.nature.com/articles/srep03141) Flickr photos tagged with hurricane Sandy to test its popularity over time. As a comparison they used atmospheric air pressure, indicating good use as a predicition.

* example of nowcasting
* useful for supporting during and after disaster - for ex predicting insurance claims

* [video](https://view.vzaar.com/4150604/video)

### Haiti crowd sourcing maps

[OpenStreet map project](https://www.youtube.com/watch?v=BwMM_vsA3aY) mapped roads following Haiti earthquake in 2010.

* this have been repeated for other disasters


### others

Another study demonstrated:

*  [traffic analysis](http://www.nature.com/ncomms/2016/160315/ncomms10793/full/ncomms10793.html) with short note in [Conversation](https://theconversation.com/big-data-shows-how-selfless-driving-could-ease-traffic-congestion-56166)
* [clean air for cyclists](http://www.news.utoronto.ca/helping-cyclists-avoid-smoggy-routes-toronto-and-montreal-new-research-u-t) with [subsequent app](http://traq-research.mcgill.ca/cycleapp/toronto/)
* your face is big data, as this russian student show using [VB application](http://www.bbc.co.uk/news/blogs-trending-36037628)


Discussion:

* it is not so much data or prediciton but actual implementation on the ground. Cited was Manchester IRA bombing.
* it could be used for area-specific warning or for ex missing child note
* concerns are ethical use of data and privacy issues
* anomaly detection, indicating problem
* evacuation procedure for eathequake
	* predicting where ppl will run when it strikes
	* using [mobile phones as seismometers](http://bayen.eecs.berkeley.edu/sites/default/files/journals/06470715.pdf)

# general references

* [Measuring indirect discrimination in machine learning](http://arxiv.org/pdf/1511.00148v1.pdf) and [article about it](https://theconversation.com/big-data-algorithms-can-discriminate-and-its-not-clear-what-to-do-about-it-45849)
* [white house big data privacy](https://www.whitehouse.gov/sites/default/files/docs/big_data_privacy_report_may_1_2014.pdf)
* [splunk, security](http://www.splunk.com/en_us/solutions/solution-areas/security-and-fraud.html)






[Google_Trends]: https://www.google.com/trends "Google trends"
[Wiki_stats]: http://stats.grok.se/ "Wiki data"