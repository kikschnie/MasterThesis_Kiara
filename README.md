**Project Title: The Impact of AI-Driven Content Moderation on User Engagement and Polarization: A Natural Experiment of Reddit.**
 
**Overview:**

This repository contains the analysis code for my master’s thesis, which investigates how the implementation of an AI-based toxicity filter in the subreddit r/politicaldiscussion affected user engagement and affective polarization in online political conversations.

The analysis is based on a Difference-in-Differences (DiD) design and compares the treated subreddit (r/politicaldiscussion) with one control subreddits (r/moderatepolitics) with an observation window 3 weeks before and after the filter implementation on July 25, 2022.

**Project Motivation**

Briefly summarize:

	•	Why this topic matters (e.g., rising polarization and platform responsibility)
 
	•	Why Reddit and the toxicity filter were chosen as a case study (tbd)
 
	•	The gap in literature your thesis addresses (automated moderation & affective polarization)

**Research Questions:**

	•	**RQ1:** How does the implementation of the AI-based Toxicity Filter impact User Engagement?

	•	**RQ2:** How does the implementation of the AI-based Toxicity Filter impact Affective Polarization?

**Methods Overview**

Summarizes my methodology (Difference-in-Differences design), treatment and control groups, time windows, and my two primary dependent variable groups:

Dependent Variables

	•	User engagement (Dicussion Quantity, Discussion Depth, Participation Breadth, Discussion Quality)
 
	•	Affective polarization (emotional + group-based dimensions)

Control Variables

	•	Post Score

	•	Average Author Age
 


**Hypotheses:**

	•	**H1:** “The implementation of the AI-based Toxicity Filter leads to a decrease in comment count per thread, as reduced emotional provocations stimulate fewer reactive responses.”

	•	**H2:** “The implementation of the AI-based Toxicity Filter leads to an increase in discussion depth, as conversations shift from broadly reactive exchanges to sustained dialogue between engaged participants.”

	•	**H3:** “The implementation of the AI-based Toxicity Filter leads to an increase in comment length, as reduced emotional provocations allow for more deliberative cognitive processing.”

	•	**H4:** “The implementation of the AI-based Toxicity Filter leads to a decrease in unique author percentage per thread, as discussions shift from widespread reactive participation to more sustained exchanges between fewer, more invested participants.”

	•	**H5:** “The implementation of the AI-based Toxicity Filter leads to less negative sentiment in political discussions as reduced exposure to identity-threatening content diminishes the activation of defensive group-based emotions that typically drive negative sentiment expression.”

	•	**H6:** “The implementation of the AI-based Toxicity Filter leads to a decrease in sentiment variance in political discussions, as reduced emotional provocations inhibit extreme emotional reactions and interrupt contagion effects that typically amplify emotional diversity within threads.”

	•	**H7:** “The implementation of the AI-based Toxicity Filter leads to decreased usage of in-group identifiers in political discussions, as reduced exposure to partisan attacks diminishes the need to reinforce group boundaries through collective self-reference.”

	•	**H8:** “The implementation of the AI-based Toxicity Filter leads to decreased usage of out-group identifiers in political discussions, as fewer toxic provocations decrease the salience of intergroup differentiation and reduce the tendency to categorize others as opposing partisans.”

**Technologies and Tools**

Include:

	•	Python (3.12.4)
 
	•	Key libraries: pandas, statsmodels, matplotlib, seaborn, scipy,
 
	•	This project was developed using Jupyter Notebook


**Structure of the Repository**

📂 /data

    └── Raw Data files in csv format due to file-size upload restrictions. Data can be provided in original .jsonl format if needed. Originally sourced at: 		https://github.com/ArthurHeitmann/arctic_shift![image](https://github.com/user-attachments/assets/ffdb33f1-0ea1-47ee-8407-44916f2ba976)

    
    └── Political Discussion Comments.csv, Political Discussion Posts.csv, Moderate Politics Comments.csv, Moderate Politics Posts.csv
    
📂 /notebooks

    └── 04_difference_in_differences.ipynb
    
📂 /results and figures

    └── Regression results

    └── Distribution
    
    └── Descriptive Statistics
    
📄 README.md

📄 Process Overview.md
