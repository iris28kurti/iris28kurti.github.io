# Climate And Chocolate

Our project is to uncover patterns in chocolate beans around the world. We'll examine relationships between chocolate bars, along with information on their regional origin, percentage of cocoa, the variety of chocolate bean used and where the beans were grown.

We found the dataset on Kaggle called, “[Chocolate Bar Ratings](https://www.kaggle.com/rtatman/chocolate-bar-ratings#flavors_of_cacao.csv),” that contains expert ratings of over 1,700 individual chocolate bars. 

The analysis process was broken into two broad phases: Exploration & Cleanup and Analysis.

We used a Jupyter Notebook to explore, clean, and reformat our data before we could begin to answer the research questions.

**Cleanup & Exploration**
* Convert Objects
* Rename Columns
* Remove null values
* Drop NA
* Replace row content to get unique values
* ecc

**Analysis**
* Top Rating Beans
* Bottom Rating Beans
* Create new df with only relevant columns and beans
* Top Country by Rating
* Top Beans by rating

**Plots**
* Average rating per year all beans
* Average rating per type of bean
* Boxplot Rating for Bean origin countries
* Average rating of the Top 5 countries by higher consistent rating by year
* Goods Flow from Company location, mean rating by years
* Boxplot, Rating for Company Location countries
* Counts of ratings vs bean origin GDPs
* Ratings vs bean origin GDPs

**Conclusions**
[Link to Presentation on Prezi](https://prezi.com/view/1OGXVRNajgLmTZ4h42fe/)

---
More info
---

* **Context**

Chocolate is one of the most popular candies in the world. Each year, residents of the United States collectively eat more than 2.8 billions pounds. However, not all chocolate bars are created equal! This dataset contains expert ratings of over 1,700 individual chocolate bars, along with information on their regional origin, percentage of cocoa, the variety of chocolate bean used and where the beans were grown.

* Flavors of Cacao Rating System:
	* 5= Elite (Transcending beyond the ordinary limits)
	* 4= Premium (Superior flavor development, character and style)
	* 3= Satisfactory(3.0) to praiseworthy(3.75) (well made with special qualities)
	* 2= Disappointing (Passable but contains at least one significant flaw)
	* 1= Unpleasant (mostly unpalatable)

Each chocolate is evaluated from a combination of both objective qualities and subjective interpretation. A rating here only represents an experience with one bar from one batch. Batch numbers, vintages and review dates are included in the database when known.

The database is narrowly focused on plain dark chocolate with an aim of appreciating the flavors of the cacao when made into chocolate. The ratings do not reflect health benefits, social missions, or organic status.

Flavor is the most important component of the Flavors of Cacao ratings. Diversity, balance, intensity and purity of flavors are all considered. It is possible for a straight forward single note chocolate to rate as high as a complex flavor profile that changes throughout. Genetics, terroir, post harvest techniques, processing and storage can all be discussed when considering the flavor component.

Texture has a great impact on the overall experience and it is also possible for texture related issues to impact flavor. It is a good way to evaluate the makers vision, attention to detail and level of proficiency.

Aftermelt is the experience after the chocolate has melted. Higher quality chocolate will linger and be long lasting and enjoyable. Since the aftermelt is the last impression you get from the chocolate, it receives equal importance in the overall rating.

Overall Opinion is really where the ratings reflect a subjective opinion. Ideally it is my evaluation of whether or not the components above worked together and an opinion on the flavor development, character and style. It is also here where each chocolate can usually be summarized by the most prominent impressions that you would remember about each chocolate.

**Acknowledgements**

These ratings were compiled by Brady Brelinski, Founding Member of the Manhattan Chocolate Society. For up-to-date information, as well as additional content (including interviews with craft chocolate makers), please see his website: Flavors of Cacao

**Inspiration**

Where are the best cocoa beans grown?

Which countries produce the highest-rated bars?

What’s the relationship between cocoa solids percentage and rating?