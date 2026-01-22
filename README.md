# Sports Popularity Across Cities: YouTube Data Analysis

## Topic and Search Parameters
For this project, I explored the topic of **sports popularity in different cities** using YouTube video data. I chose three search terms:

- `"seattle sports"`  
- `"vancouver sports"`  
- `"los angeles sports"`  

The goal was to compare which sports and teams are most discussed in each city. These searches were selected to focus on local sports coverage and to capture trends in what sports content people are consuming online.

---

## Purpose of the Comparison
I wanted to see how **sports culture differs across cities**. Seattle, Vancouver, and Los Angeles each have a variety of professional and amateur sports teams, and I was curious which teams, sports, or channels dominate YouTube content for each location. This comparison allows us to observe local popularity, trends, and unexpected patterns in sports coverage.

---

## Word Cloud Comparison

### Seattle
- The word cloud was dominated by the **names "Brock" and "Salk"**, due to the local Brock and Salk podcast channel having high coverage of Seattle sports.  
- I expected words like **Seahawks**, **Mariners**, **game highlights**, and **press conferences** to be more prominent, but these appeared less frequently.  
- Other common words included terms describing player actions, like **"dive"**.

### Vancouver
- The most common words were **"Vancouver"** and **"sport"**, which matched my search terms.  
- I was pleased to see **Canucks** (hockey) and **Whitecaps** (soccer) appear, though **hockey was less prevalent than expected**.  
- Terms like **"BC"** and **"Place"** referred to Vancouver's stadium, **BC Place**.  
- The word **"soccer"** appeared prominently, which was somewhat unexpected given Vancouver's strong hockey culture.

### Los Angeles
- The word cloud prominently featured **LA sports teams**, including **Angels** and **Dodgers** (baseball), followed by **Clippers, Chargers, Lakers, and Kings**.  
- This was closer to my expectations and showed a clear focus on local teams rather than general or unrelated sports content.  
- Overall, Los Angeles produced the **cleanest and most relevant results**, with a strong representation of local sports teams.

### Summary
- The **best results** (most relevant word cloud) came from Los Angeles.  
- The **least relevant results** came from Seattle, dominated by a single popular podcast rather than teams or sports events.  
- Vancouver was intermediate, showing some local teams but also broader terms from the search.

---

## Possible Reasons for Observed Patterns
- **Seattle:** High dominance of Brock and Salk podcast may be due to YouTube search algorithm prioritizing popular channels over specific teams.  
- **Vancouver:** Soccer may appear more prominently because of recent coverage or video metadata including "soccer," and the search term `"sports"` is broad.  
- **Los Angeles:** Large number of professional teams across multiple leagues provides a richer variety of content and higher visibility of team names.

---

## Improvements for Future Research
- Use **more specific search terms** like `"Seattle Seahawks highlights"` or `"Vancouver Canucks recap"` to reduce irrelevant results.  
- Increase the number of videos collected per search to improve statistical significance.  
- Consider filtering out podcast channels or repeated channels to focus solely on team coverage.  
- Compare multiple types of content: highlights, fan reactions, and news channels separately.  
- Incorporate **date/time filters** to analyze trends over specific periods (season, playoffs, etc.).

---

## Unexpected Findings
- I was surprised by the dominance of a **single podcast** in Seattle, which skewed the word cloud.  
- Vancouver’s word cloud emphasized **soccer over hockey**, which was unexpected given the local popularity of hockey.  
- Los Angeles results were closest to expectations, with multiple teams represented accurately.

---

## Assets

### Word Clouds
![Seattle Sports Word Cloud](/img/seattle_sports_wordcloud.png)  
![Vancouver Sports Word Cloud](/img/vancouver_sports_wordcloud.png)  
![Los Angeles Sports Word Cloud](/img/la_sports_wordcloud.png)  

### CSV Files
You can download the collected data here:  
- [Seattle Sports CSV](./assets/seattle_sports.csv)  
- [Vancouver Sports CSV](./assets/vancouver_sports.csv)  
- [Los Angeles Sports CSV](./assets/la_sports.csv)

---

*This analysis was completed using data collected via a YouTube crawler built in Python and executed in Google Colab.*
