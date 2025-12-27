---
title: "Political Speech on Twitter: A Sentiment Analysis of Tweets and News Coverage of Local Gun Policy"
author: "Mohamed Lemine M’Bareck"
date: "May 2019"
---

# Project Overview

This repository contains the R code and data for my Master’s thesis at the **University of Arkansas**. The project utilizes automated content analysis and text mining to compare how state politicians and local news media frame the debate surrounding gun policy in Arkansas.

## 📌 Research Summary
The study examines ~5000 gun-related tweets from three Arkansas politicians (Charlie Collins, Denise Garner, and Greg Leding) and ~4000 news articles from three local newspapers. The analysis focuses on:
* **Framing:** How language is used to construct narratives.
* **Sentiment:** Measuring the emotional valence (fear, anger, trust, etc.).
* **Word Usage:** Identifying the most frequent terms and their impact on political narrative.

---

## 🛠 Methodology
The analysis follows a "Tidy" text mining approach using the **R Programming Language**.

### Process Workflow
1. **Data Collection:** Tweets retrieved via `rtweet` API; News articles via America’s News database.
2. **Preprocessing:** Tokenization, cleaning (URLs, punctuation, stop-words), and bigram clustering.
3. **Sentiment Scoring:** Lexicon-based analysis using the **Bing** and **NRC** dictionaries.
4. **Visualization:** Data synthesis using `ggplot2`.

Methodology Diagram
<img width="859" height="844" alt="image" src="https://github.com/user-attachments/assets/c86b435a-ba26-4fd2-b5e9-c338cbfdd1b4" />

---

## 📊 Key Findings

### 1. Political Framing
Politicians used highly polarized "bigrams" to appeal to their bases. For example, Rep. Collins focused on "public safety" and "mass shooters," while Sen. Leding focused on "red flag" and "flag laws."

Political Frames
<img width="956" height="747" alt="image" src="https://github.com/user-attachments/assets/8f37e3d2-ca00-498e-96f0-0d550bfe3d91" />

### 2. Emotional Analysis
Using the NRC Emotion Lexicon, the analysis revealed that political tweets were characterized by high levels of **fear** and **anger**, whereas news media coverage expressed significantly higher levels of **trust**.

| Twitter Emotional Valence | News Media Emotional Valence |
| :---: | :---: |
|<img width="872" height="724" alt="image" src="https://github.com/user-attachments/assets/4201ce3f-3131-4985-9ce3-0383f5c2ea0e" /> | <img width="860" height="688" alt="image" src="https://github.com/user-attachments/assets/51637aba-d76b-48bd-9a64-74fda7050062" />


### 3. Sentiment Over Time
The study tracked how sentiment shifted throughout the 2018 election cycle. While politicians remained largely negative, news media maintained a more neutral, fact-based tone.

| Politicians Sentiment | News Media Sentiment |
| :---: | :---: |
|<img width="873" height="704" alt="image" src="https://github.com/user-attachments/assets/afc66ddd-5e31-4355-a6c9-eca1d06252d6" /> |<img width="873" height="688" alt="image" src="https://github.com/user-attachments/assets/a93d3e6c-7734-4bff-a9b4-68325b15f6e6" />




## 🎓 Contact
**Mohamed Lemine M’Bareck**  
University of Arkansas  
School of Journalism and Strategic Media  
Email: [mmmbarec@uark.edu](mailto:mmmbarec@uark.edu)
