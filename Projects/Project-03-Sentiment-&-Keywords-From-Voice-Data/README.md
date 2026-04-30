## Project 03: Text Cleaning, Sentiment Analysis & Insight Extraction

### Overview
This phase of the project focused on deepening my use of Python to clean unstructured text data, conduct sentiment analysis, and translate findings into visual insights.

Building on earlier work with employee voice data, I refined the process of preparing text for analysis and applied sentiment scoring using TextBlob to better understand patterns in employee feedback from Glassdoor and YouTube.

The goal was to move beyond raw feedback and begin quantifying employee sentiment while still preserving the context behind employee experiences.

---

### Objective
To improve the reliability of text analysis and extract meaningful insights from employee voice data through structured cleaning, sentiment scoring, keyword exploration, and visualization.

---

### What Was Done
- Cleaned and preprocessed employee voice data using Python  
- Applied text processing techniques to improve data quality  
- Removed noise such as punctuation, stop words, and inconsistencies  
- Conducted sentiment analysis using TextBlob  
- Explored keywords and recurring language patterns  
- Converted sentiment results into visualizations  
- Interpreted results to extract patterns and insights  

---

### Key Questions Explored
- How can text data be structured to improve sentiment analysis accuracy?  
- What patterns emerge when sentiment is quantified and visualized?  
- How do sentiment trends connect to previously identified themes such as burnout and management issues?  
- How do Glassdoor and YouTube differ as employee voice data sources?  
- What are the limitations of sentiment analysis when applied to real-world feedback?  

---

### Findings Summary
Analysis of employee voice data from Glassdoor and YouTube revealed clear differences in how employees communicate their experiences.

Glassdoor reviews tend to be more structured and constructive, often outlining pros, cons, and actionable feedback. This makes it easier to identify patterns and assess sentiment with clarity.

In contrast, YouTube content is more emotionally driven and less structured. While this makes themes slightly harder to extract, it provides deeper context into day-to-day operations, work pace, and work-life balance challenges.

Together, these platforms complement each other — Glassdoor offering clarity and direction, while YouTube provides depth and lived experience.

For a more detailed summary, see the [Findings Summary PDF](./deliverables/project-3-findings-summary.pdf).

---

### Key Insights
Refining the data cleaning process significantly impacted how well sentiment analysis tools were able to interpret the data.

While sentiment scoring helped quantify employee feedback, the underlying themes remained consistent — burnout, workload pressure, and ongoing concerns related to management and support.

This reinforced the idea that while tools can help measure sentiment, the quality of insights depends heavily on how well the data is prepared, structured, and interpreted.

Additional insights included:
- Sentiment analysis provides direction, but not full context  
- Emotional language can skew sentiment scoring if not interpreted carefully  
- Structured feedback from Glassdoor is easier to quantify  
- Unstructured content from YouTube provides richer storytelling and operational context  
- Combining both sources creates a more complete view of employee experience  

---

### Deliverable(s)
This section stores polished project outputs connected to this phase of the analysis.

- [Findings Summary PDF](./deliverables/project-3-findings-summary.pdf) *(to be added)*  
- [Cleaned datasets](./data/cleaned)  
- [Python scripts for preprocessing and sentiment analysis](./python)  
- [Visualizations of sentiment distribution and trends](./visuals)  

---

### Tools Used
- Python  
- Pandas  
- NLTK (text cleaning)  
- TextBlob (sentiment analysis)  
- Data visualization tools  

---

### Reflection
This project reinforced the importance of data preparation in the analytical process.

Cleaning and structuring text data plays a critical role in making sure insights accurately reflect the underlying message. Even small inconsistencies in text can affect the reliability of results.

It also highlighted that while tools like TextBlob are useful, they should be used alongside contextual understanding rather than treated as a standalone source of truth.

---

### Areas for Improvement
- Improve text cleaning to better handle context-specific language  
- Explore more advanced sentiment models for higher accuracy  
- Incorporate topic modeling to better group themes  
- Strengthen the connection between sentiment results and operational recommendations  

---

### Connection to Previous Work
This phase builds on earlier analysis of employee voice data by improving how insights are extracted and measured.

While previous work identified themes qualitatively, this stage introduces a more structured and measurable approach to analyzing employee sentiment.

---

### Next Step
The next phase will focus on bringing together operational structure, employee sentiment, and management influence to support the final pilot intervention and case study on attrition.
