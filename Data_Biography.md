# Data Biography

## Student Number: XXXXXXX

---

### 1. Who collected the data?

_The background database manager of Airbnb collates the interactive data of renters, homeowners and houses sourced from publicly available information from the Airbnb platform.[1]_

---

### 2. Why did they collect it?

The data they collect are mainly helpful for the management of the platform and financing for the platform; it is also helpful for customers to quickly find houses that meet their needs. The constantly improving database allows users to have a better experience when using the website, thereby increasing user stickiness and ultimately bringing more revenue to the platform.

---

### 3. How was it collected?

The data sets were assembled by programmatically compiling public information from Airbnb’s website. The data sets attempt to locate all the listings within London and then visit each listing page to collect listing data, including the listing ID. The listing ID allows an analysis of the number and information of listings posted.[2]The data has been analyzed, cleansed, and aggregated, where appropriate, to facilitate public discussion.[1]

---

### 4. What useful information does it contain?


The data reflects the total number of listings in the London Airbnb market and its breakdown. The listing id is identified on each page by a unique identifier. Including basic information of hosts (host listings count, id) and basic information of listings (Room type, price, bathroom, bedroom, availability,) And latitude and longitude can reflect the listing location. The number and score of comments indicate the number of visits to the list and the list's quality, respectively. In particular, the host response time/rate, host acceptance rate, and other information related to the host's service quality. Neighborhood and related factors reflect the surrounding environment.

---

### 5. What useful information is it missing?

When License and Bathrooms are structurally missing in this data, part of reviews are missing with the number of reviews. And bedrooms, bathroom type, neighborhood, host response time, host acceptance rate, and review score are missing completely at random when they are considered useful for research.

---

### 6. To what extent is the data 'complete'?

The data contains complete necessary information of the room based on the listing id, including room type, bedroom, price, location, etc. Simultaneously, the information of host required and Number of reviews is complete (although the reviews' content is incomplete). Thus the research done by analysts with this type of key field is robust. However, the license, bathroom, calendar, etc., are with all null values, structurally missing. Compared with the data in July 2020, the decision-making factors are crucial as prices such as cleaning and security deposits are missing. However, the host response time/rate, host acceptance rate, and other information related to the host's service quality and the review score showing the room quality are missing completely at random. This type of information is beneficial for data analysts but is incomplete. Thus the robustness of the research based on this has also declined.

---

### 7. What kinds of analysis would this support?

The analysis could be supported based on the opportunity provided by complete data; for example, the latitude and longitude shown location can help fix the questions: How many listings are in my neighborhood, and where are they? And the price can help work out: How much are hosts making from renting to tourists.[1] The correlation between Airbnb's cluster on hotels and other parts of the tourism economy [3]. Because necessary information such as the number, location, and price of Airbnb hotels are Complete, the research results will be convincing. Using this kind of complete data for visualization can intuitively and accurately express their correlation and influence. Due to review score missing completely at random, research based on the reviews can only be limited to using the number of reviews, which reflects the number of visits to a listing, to study the relevance of hotel visits to local hotel prices. Besides, it's also feasible to use complete neighborhood information to study Airbnb hotels' impact on the surrounding environment.

---

### 8. What kinds of analysis would it _not_ support?

Unsupported research is mainly caused by random missing data related to listing quality and host's service. For example, host response time/rate, host acceptance rate are essential for studying the impact of host service quality on local hotels' development and the tourism industry's growth. Still, the random missing data will make the results of the research robust and reliable Lower. Similarly, the review score reflects the quality of the listing very well. Still, there are also random missing relevant data, so the research based on this field is difficult to support.

---

### 9. Which of the uses presented in Q.7 and Q.8 are _ethical_?

In most analyses, the key field data used is collected from Airbnb's public platform (transparent and allowed to be disclosed by the host), which is ethical. For example, studying the correlation between Airbnb's price and the local tourism economy's development can reference local hotel planning, and people will also strongly support it. It is also considered feasible to use the number of reviews to indicate the number of visits to a listing. It is ethical and useful to study the correlation between Airbnb's popularity and the popularity of local attractions and business districts. But when it comes to geographic location, there are ethical issues. When the listings' longitude and latitude are not displayed on the Airbnb website, the platform will only provide customers with the host's exact location information after the customer's reservation is confirmed. The purpose of this is to protect the privacy of the host. However, the longitude and latitude data showing the exact location information are directly disclosed on the Inside Airbnb data platform, which exposes all listings' geographic location and brings security risks to the host, which is unethical. Furthermore, for data such as host response time/rate and host acceptance rate, which are missing randomly and can't make the research results more credible, it remains verified whether these data have passed the host's permission to been made public. The investigation revealed: One fundamental flaw of the default booking system in Airbnb – which requires approval from the host. [4]If the host is accused of discrimination because of its low host acceptance rate, is this reasonable? All of these infringe the host's right to privacy. On the other hand, this can also indicate that the platform allows for discrimination, which is clearly against morality.

 
### 10. Appendix

[1]	M. Cox, “Inside Airbnb.” http://insideairbnb.com/about.html.

[2]	M. Cox and T. Slee, “How Airbnb’s data hid the facts in New York City,” Tomslee.net, pp. 1–16, 2016, [Online]. Available: http://tomslee.net/how-airbnb-hid-the-facts-in-nyc.

[3]	J. Reades, “specific analysis.” https://casa-students-2020.slack.com/archives/C01AD9B160K/p1606317567244200?thread_ts=1606315748.243000&cid=C01AD9B160K.

[4]	“IS THERE AN ETHICAL PROBLEM WITH USING AIRBNB?,” 2017. https://www.themediterraneantraveller.com/airbnb-ethically/.

