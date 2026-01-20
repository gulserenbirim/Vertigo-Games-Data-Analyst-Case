# Vertigo-Games-Data-Analyst-Case

In this task, I conducted a 30-day projection simulation to compare two distinct business strategies:

Variant A – Aggressive Monetization: Focused on maximizing short-term revenue through higher ad frequency

Variant B – User-Centric Retention: Focused on long-term growth by prioritizing user experience and retention

Analysis Results and Technical Evaluation:

a) DAU Comparison on Day 15:
Variant B clearly led in Daily Active Users. By keeping ad frequency lower, it preserved a better user experience, which translated into significantly stronger retention performance.

b) Total Revenue on Day 15:
At this stage, Variant A generated higher revenue. The increased ad exposure created a short-term cash flow boost; however, the negative impact on user churn had not yet fully materialized.

c) Need for a Strategic Pivot by Day 30:
Yes. By Day 30, the overall outcome shifted:

Variant B: $176,978

Variant A: $176,807

Thanks to its stronger and more loyal user base, Variant B created a “compounding growth effect” that ultimately surpassed the short-term gains of aggressive monetization. This clearly demonstrates the importance of sustainable, retention-driven growth.

d) Impact of the 10-Day Sale Starting on Day 15:
The sale benefited Variant B more. A 1% increase in purchase rate had a much larger impact when applied to a bigger and more loyal DAU pool, resulting in significantly higher incremental revenue.

e) Effect of a New User Source Introduced on Day 20:
After the additional user acquisition boost, Variant B reached a total revenue of $183,038. Its retention model

0.52
⋅
𝑒
−
0.10
(
𝑥
−
1
)
0.52⋅e
−0.10(x−1)

proved far more effective at keeping new users engaged within the ecosystem. Variant A, in contrast, struggled to retain these users at the same efficiency.

f) Final Strategic Recommendation:
Based on the analysis, the best long-term investment is Option 2 – a permanent new user source. While temporary discounts can generate short-term revenue spikes, continuous top-of-funnel growth delivers significantly higher ROI and provides a much more scalable and sustainable growth trajectory.

<img width="609" height="206" alt="image" src="https://github.com/user-attachments/assets/59fa814b-150e-4dfa-929e-9571608e03fc" />


Task 2: Player Experience & Deep Economy Analysis

In this task, I didn’t rely solely on raw data. I combined quantitative analysis with direct gameplay observations to better understand the player psychology behind the metrics.

Competitive Fairness: The “SVP” Insight
During my playtests, I noticed a common frustration point: players who perform exceptionally well in a match—high kills, strong effort—still lose rank points simply because their team underperforms.
The data supports this: 31.75% of losing players (26,481 records) fall into the “High-Effort” category, meaning they contribute significantly despite the final outcome.
To reduce churn among these valuable users, I recommend implementing an SVP (Second Valuable Player) system, which would grant trophy protection to the best-performing player on the losing team.

Progression Efficiency: “Grinders” vs “Elite” Players
Another pattern I observed is that some players climb leagues not because of skill, but purely through excessive playtime.
The data confirms this behavior: 7.33% of the player base (21,298 users) are classified as “Grinders.” They have low win rates (below 45%) but extremely high session durations.
From a monetization perspective, this creates a clear gap: an “Elite” player generates 0.74 IAP revenue, while a “Grinder” generates only 0.33, despite spending similar amounts of time in the game.
This suggests that the progression system should be rebalanced to reward actual skill (win rate) more than simple time investment.

Matchflow: The “Feeding” Loop Problem
In several matches, I observed a problematic cycle where low-skill players repeatedly respawn and die almost immediately. This creates highly one-sided games and ruins the overall experience.
The data reflects this as well: the “Feeder” segment, consisting of 26,864 users, has an average win rate of just 35.88%.
To address this, I recommend introducing Dynamic Spawn Times—gradually increasing respawn delay after consecutive deaths. This would help break the loop and stabilize match balance.

Geographic ARPU Potential
One of the key insights from the analysis is that not all markets behave the same.
For example, Gabon shows an exceptionally high ARPU of 6.66, while South Korea represents a high-volume market with 1,746 users and an ARPU of 1.15.
Based on this, I suggest a differentiated strategy:

Deploy targeted high-value IAP bundles in high-ARPU boutique markets like Gabon

Focus on optimizing rewarded ads and engagement-driven monetization in high-volume markets like South Korea


Key Visualizations & Deep-Dive Insights

Revenue Streams: IAP vs. Ad Revenue
Observation: In-App Purchases (IAP) account for 85.8% of total revenue, while Ads contribute 14.2%.

Insight: Our economy is heavily driven by direct purchases. Any strategy that harms long-term user retention (like aggressive ad frequency) risks our primary 85.8% revenue stream.

<img width="642" height="633" alt="image" src="https://github.com/user-attachments/assets/7b205d53-0530-46f7-8e5d-e136fc1b08b2" />


Competitive Fairness: The SVP Potential
Observation: 31.75% of losing players (26,481 users) are classified as "High-Effort" candidates.

Insight: These players invest significant time (High Session Duration) and energy into matches they ultimately lose. Implementing an SVP (Second Valuable Player) bonus for this top 31.75% will protect them from "Rank Churn" and improve long-term engagement.

<img width="980" height="610" alt="image" src="https://github.com/user-attachments/assets/16cc8ce3-c02a-4eff-bab1-1e04d4440c24" />


Player Segmentation: Skill vs. Time Investment
Observation: Elite players (Win Rate: 81%) generate 0.74 ARPU, while Grinders (Win Rate: 30%) generate only 0.33 ARPU despite high playtime.

Insight: There is a clear correlation between skill and monetization. We should focus UA (User Acquisition) efforts on competitive channels that bring in high-skill "Elite" players to maximize ROI.

<img width="629" height="99" alt="image" src="https://github.com/user-attachments/assets/d05a6832-5dcc-4684-91f5-12a9f63af341" />



Match Flow: The "Feeder" Loop Analysis
Observation: The Feeder segment (26,864 users) has a stagnant average Win Rate of 35.88%.

Insight: This segment is likely trapped in a negative feedback loop. Introducing dynamic respawn timers or "pity mechanics" after consecutive deaths is essential to improve the FTUE (First Time User Experience) for these struggling players.

<img width="1003" height="587" alt="image" src="https://github.com/user-attachments/assets/8e06100e-7a3e-4c20-8163-7d56e278d948" />



Global Market Potential: ARPU by Country
Observation: Gabon shows the highest per-user value with a 6.66 ARPU, while South Korea provides the highest volume (1,746 users) with a healthy 1.15 ARPU.

Insight: Our marketing strategy should be two-fold: High-ticket specialized offers for "Whale" boutique markets like Gabon, and community-driven engagement events for high-volume regions like South Korea.

<img width="500" height="194" alt="image" src="https://github.com/user-attachments/assets/ec637663-f4d9-44c3-9b70-15e24d02f257" />


Player Segmentation by Spending: Whale vs. Dolphin vs. Minnow

In this analysis, I segmented the player base according to purchasing behavior to better understand the differences between paying and non-paying users and to identify monetization opportunities.

Key Findings:

Whales (High Spenders):
This is the most valuable segment, consisting of 2,907 users. They are also the most engaged group, with an average session duration of 7,920 seconds and 20.5 match starts per user. In addition, they have the highest performance level, with an average Win Rate of 64.16%. This confirms that high spenders are not only financially valuable but also deeply invested in the game.

Dolphins (Mid Spenders):
This segment includes 1,698 users. Their engagement metrics are very close to Whales, averaging 6,713 seconds of playtime and a 62.37% Win Rate. While they demonstrate similar behavioral patterns, their monetization contribution is noticeably lower.

Minnows (Low Spenders / Non-Payers):
The vast majority of the player base falls into this category, with 286,007 users. They are essential for maintaining matchmaking liquidity, but their engagement is significantly lower, averaging only 2,527 seconds of playtime and 6.5 match starts per user.

Strategic Insights & Recommended Actions:

Whale Loyalty Strategy:
Since Whales are the core revenue drivers and the most active players, the in-game economy should prioritize high-value, exclusive content tailored to them—such as VIP passes, premium bundles, and rare cosmetics. The goal is to maintain their high satisfaction and engagement levels without negatively affecting competitive balance.

Dolphin Conversion Strategy:
Dolphins show almost the same level of engagement as Whales but generate less revenue. This makes them the most promising group for monetization growth. Targeted offers such as “limited-time deals” or progressive step-up bundles could effectively encourage these users to transition into the Whale segment.

Minnow Retention & Monetization Strategy:
The relatively low session duration of Minnows indicates a higher risk of early churn. For this group, I recommend increasing the use of Rewarded Video Ads to monetize their activity without requiring direct purchases. This approach allows the game to generate value from a large non-paying audience while keeping them engaged.

<img width="628" height="202" alt="image" src="https://github.com/user-attachments/assets/39475301-da07-43d4-88d2-def40f582f5c" />



Daily Revenue Trend (Satın Alma vs. Reklam)

Observation: In-App Purchase (IAP) revenue shows high volatility with sharp peaks (reaching 2500+), while Ad Revenue remains extremely flat and stable around the 250-300 range.

Insight: The peaks in IAP suggest that our revenue is highly sensitive to live ops, events, or specific offers. The flat line in Ad revenue indicates that we are not effectively scaling ad monetization with player activity; there is a significant opportunity to implement "Event-Based Rewarded Ads" to mirror the successful peaks seen in IAP.

<img width="1065" height="580" alt="image" src="https://github.com/user-attachments/assets/8f03a671-f29b-45bb-beeb-69f218099708" />


Correlation: Impact of Losses on Session Duration

Observation: There is a clear positive correlation (upward-sloping regression line) between the number of losses and total session duration.

Insight: At first glance, this seems counterintuitive (more losing leads to more playing). However, this suggests a "Just One More Match" psychological effect where players keep playing to "correct" a loss.

Risk Factor: While this increases short-term playtime, it is a high-churn risk. If a player ends their session on a long losing streak (as shown by the dense clusters at high loss counts), their "Recency Bias" will make them less likely to return the next day. This further reinforces the need for the SVP (Second Valuable Player) rewards we discussed earlier to end a session on a positive note even after a loss.

<img width="945" height="611" alt="image" src="https://github.com/user-attachments/assets/d16da7b6-6572-4b59-bec6-97031bd31bb7" />




