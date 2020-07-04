# DIGHUM101 - Summer 2020 

![manga](images/totoro.jpg)


*Go to:*

[Individual Abstract](#id)

---

## Group Project Abstract: Distant and Close Reading

### Intro
***Distant Reading*** is a form of literary analysis performed in a computer program by aggregating and analyzing text; the program identifies literary genres and envisions plots by mining through each word and phrase. ***Close reading*** is done with first hand reading and analysis of text, which has led to great insights and advancements in literature from unique styles and themes derived from texts.

### Research Question
Distant Reading is a relatively new term that may cause many to ask exactly what it is and why it's important. Based on the readings on distant learning and the digital humanities, the concepts, as well as methods for testing Distant Reading are further explored. My group and I worked collaboratively, researching several articles which provide a brief overview, to answer our questions: 
* **What is this *new* concept?** 
* **How does it compare with the method of Close Reading?** 
* **What can we learn from it?**

### Methods/Materials
Machine learning is used to analyze text and identify genres and styles. Distant reading is also tested by using it to categorize and formulate topics on a corpus of ekphrasis poems - which is recognized for its figurative references of visual arts and metaphors, words that differ from their literal meaning and manner of speech. 

### Findings
Distant learning quickly analyzes a great amount of text in the manner of minutes, and is able to discern between genres and styles in the literature. However, when faced with the corpus of poems, Distant Reading gives misinterpretations of the text. 

### Dr. Nan Z Da
Dr. Nan Z Da, explains the literary complexity present with current computational methods and the tradeoff between precision and efficiency. Further research in computational methods are needed to address the issues identified by the authors, as there is still no computationally effective way to analyze large amounts of text without sacrificing the important nuances in literature.

### Discussion
By examining the issues, trade offs, and benefits of Distant reading, the readings also identify its shortcomings. Our group collectively feel that distant reading is a very beneficial tool, but should not be the sole instrument in analyzing data. 

### Reflection
Our group worked well together, splitting up the readings, taking notes and informing each other of key points. We reached our own conclusions on the materials read while we learned about the topic, methods used, and revealed the findings. After which, we created a presentation to present our topic and findings to our peers, engaging them to share their own views. Even though we are from different backgrounds, we were able to easily come together, each of us combining our efforts to the project. It was a truly great experience! 

--- 
<a id="id"></a>
## Individual Project Abstract: *An Analysis of Genre in Anime*


### Intro
Japanese animation, anime, are often characterized by its vibrant characters, distinct graphics, and outlandish themes. The themes of these, sometimes, unconventional and quirky pieces, place them into a number of genre. Like many forms of media, for example US movies, tv shows, books, etc., anime has prevalent genre crossing, meaning that titles often fall into more than one genre.

### Research Questions
<ol>
<li>Does splitting genres change the data? Or affect ratings?</li>  
<li>Do higher genre counts have higher scores?</li>
<li>What is the leading anime genre?</li>
<li>Are ratings dependent on genre?</li>
</ol>
### Materials
I will use the MyAnimeList dataset that has been aquired through kaggle. Predominently sourced from MyAnimeList.net
The dataset includes over 12,000 data and consists of: anime-id, title(name), genre, type, # of episodes, rating, and members with the anime in their list. 
The members may or may not have rated the title in their list.

[Kaggle](https://www.kaggle.com/CooperUnion/anime-recommendations-database)

### Methods & Techniques include the following:
1. Data Preparation
2. Data Cleaning
3. Descriptive Statistics
4. Data Visualization
5. Results

Modules used will include: matplotlib, numpy, pandas, string, Dataframe, pyplot

### Results
* The original dataset showed inconsistant counts on genres due to multiple values in column rows. The original dataset showed that the genre with the highest frequency was ***Hentai***. However, further analysis showed that ***comedy*** and ***action*** had the highest counts.
* Genre with the lowest occurances of genre **and** members, have much lower average ratings compared their counterparts.
* **Top 5 genres, based on members:** *Action, Comedy, Drama, Adventure, Hentai*
* **Top 5 genres based on count:** *Action, Comedy, Drama, Adventure, Hentai*
* **Top 5 genre based on avg rating:** *Josei, Mystery, Drama, Action*
* ***Bottom genres in all categories (low members, frequencies, and average rating):*** Vampire, space, super power samurai

### Conclusion
I enjoyed learning more about a media form that I frequently view. Research on anime is still quite limited. Much of what I found focuses on the styles and designs of characters. One university-based research paper performed an analysis on the complexity and challenges of defining genres. 

Going in, I thought the genres would appear at a different frequency seperately than before they were split. Yet, I didn't expect the number one genre, before seperating them, was hentai. It was thought prevoking to see the extent of the difference, and I can't help bu wonder if authors/directors notice this shift in genre popularity...    

#### In the future
* I would be interested in seeing if a viewers gender has an influence on the ratings? Who rates titles more often?
* Are more seasoned members more permissive when ranking? Or does news of top anime travels - lesser known stay unknown, because not many good reviews come out?

 [Back to Top](#DIGHUM101---Summer-2020)

