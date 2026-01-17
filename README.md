# Instagram Reach & Engagement Analysis (Task 3)

## 📋 Project Overview
This project focuses on analyzing Instagram engagement patterns to identify optimal posting strategies. By processing 7 relational datasets (Users, Photos, Likes, Comments, Follows, Tags, and Photo_Tags), I identified the specific signals—timing, hashtags, and content formats—that drive maximum audience interaction.

## 🛠️ Technical Implementation
* **Data Engineering:** Unified multiple CSV files into a relational data model to track user-content interactions.
* **Engagement Metrics:** Calculated the **Engagement Rate per Follower**, providing a more accurate measure of content quality than raw like counts.
* **Time-Series Analysis:** Parsed raw timestamps to identify peak activity windows and categorize engagement by hour and day.
* **Hashtag Frequency Mapping:** Integrated the tagging system with engagement data to isolate the most viral hashtag clusters.

## 📊 Results & Performance

- **Optimal Posting Time:** Identified **8:00 AM – 9:00 AM** as the peak window for initial engagement.
- **Top Content Format:** **Single Photos** and **Videos** consistently outperformed Carousels in engagement-to-follower ratio.
- **Viral Trigger:** The hashtag **#smile** was identified as the top-performing tag by frequency and reach.
- **Content Strategy:** Posts using query-based captions saw a significant boost in comment activity.

## 📁 Repository Contents
- `Instagram_Analytics.ipynb`: Complete Python source code for data cleaning, merging, and analysis.
- `Strategy_Document.pdf`: One-page business strategy including a content calendar and growth recommendations.
- `Engagement_Visuals.png`: Dashboard featuring engagement trends by hour, day, and content type.

## 🚀 Growth Strategies for Alfido Tech
1. **The 8 AM Rule:** Schedule all primary content for the 8:00 AM traffic peak.
2. **Hashtag Optimization:** Use high-volume viral tags (e.g., #smile) combined with niche industry tags.
3. **Engagement Loops:** Use "Question" captions to trigger the algorithm's comment weight.
4. **Mid-Week Focus:** Prioritize posting on Wednesday and Thursday for maximum weekly resonance.
5. **Verified Interactions:** Focus on engaging with verified users to build social proof and authority.
