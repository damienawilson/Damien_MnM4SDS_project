# Iraqi Demographics Python Project

## Study Area

I decided to focus on Iraq for my project due to my interests in the Middle East, geography, and politics. Furthermore, I am pursuing a History major (in addition to GIS) with its concentration being the Middle East, so I thought that this would be an interesting way to utilize my expertise from both my majors.

Iraq is a Middle Eastern country situated in the middle of the region, neighboring six other countries. Arguably, Iraq’s two most influential neighbors are those of Saudi Arabia to its southwest and Iran to its east. These two countries exert much influence over the country's politics and geography in the fledgling democracy of Iraq. Much of this is due to the ongoing Saudi-Iranian cold war, in which both countries compete to be the predominant power of the Middle East. Recently, on October 10th of 2021, the Iraqi parliamentary election saw the rise of a pro-Iraqi, anti-imperialist (focused mainly towards Iran and America), majority Shi’i movement. This movement, known as the Sadrist Movement, currently holds the most parliamentary seats if preliminary results are to be found legitimate.

My main goal is to determine what Iraq looks like in its current state politically and socially. There are many news articles analysing the current situation that I would be able to use to understand the situation better or even build upon my project further. In addition to this, I am sure that there are many scholarly articles from 2005 onwards that can describe historical trends in Iraqi ethnic and religious politics, Iranian influence, and the successes and failures of Iraqi democracy.

## Question/Task

My main task would be to compile population data (including political , religious, and ethnic makeup) of each of Iraq’s 19 governorates (provinces) and visualize this data in multiple ways. If possible (though I am not sure how feasible this is), I would like to look at the population demographics for the districts of each governorate as well. Furthermore, I would like to do this for each of Iraq’s 5 parliamentary elections (those conducted after the approval of the 2005 Constitution by referendum). In addition, I could potentially collect population data from each year (or as many as possible) to better increase the accuracy of any models that may be used or developed. Combining this data would allow population trends to be visualized and possibly allow a better understanding of Iraq politically, socially, and geographically. If possible, I would also like to look at possible predictions for future trends in politics and areas of Iraq that are susceptible to Iranian influence.

## Potential Sources of Data

Potential sources of data would vary and include (but not be limited to) both Iraqi and independent reportings of election results, UN demographic data, NGO (or other independent project) reports, and open source datasets that look to be legitimate. This may include estimates, especially in regards to population data. Data concerning the influence of Iran or other outside political entities would be much more difficult to determine. It is possible that estimates or reports of central government control, as well as various militia control (which have a variety of loyalties) could be used.

I expect that the size of data would include voting and population demographics for each election year at the very least. More data could (and should) be collected for years in between each election to strengthen the overall population dataset. At most, I would expect around 17 (if data is only being taken since the establishment of the Iraqi democracy) points of data for each category (such as Sunni pop. %, Shi’i pop.%, etc.) for each governorate (and hopefully district).

This data would either be raw data retrieved from reports and election results that needs to be processed, or hopefully already processed shapefiles or other forms of vector data that can be used either by python or by ArcGIS. If it is not, I would have to do this myself.

The limitations of the data are mainly that there will likely be mainly only estimates to work with due to the chaos that existed (and still exists) in Iraq since the establishment of its democratic government. It is also likely that the small sample size of the data (in terms of the number of elections or even since 2005) will not allow accurate predictions of population or voting trends to be made. Furthermore, if little to none of the data is processed or cleaned, that would require me to do a lot of work to do so.

## Python Tools

I would like to use Pandas to organize the data. Numpy and SciPy could both be used to analyse the data alongside Pandas. I would also use Matplotlib to visualize the data. I may attempt to use a regression line to predict future trends, but this may not be feasible due to the small data samples.

## Envisioned Challenges

The biggest challenges that I would face in the project would be compiling and organizing the data from multiple sources and determining the best way to make sure the analysis of this data is accurate. Determining the influence of various political entities within Iraq may be next to impossible (or at least lead to any visualization not including the entirety of Iraq). Afterall, I am only a single person. However, I do not believe that visualizing the population data from the last two decades will be difficult if it can be compiled and organized.

## Exploratory Data Analysis

First off, I will compile the data into one or two large dataset/s. Then I will either visualize the data through Matplotlib or convert it to shapefiles that can be used in ArcGIS for better visualization. I may even animate the maps if I have time using Photoshop. I would also show certain trend predictions through graphs if applicable.
