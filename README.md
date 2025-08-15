# womens-football-sponsor-insights

Final project for the Elements of AI Course.

## Summary

This project uses AI-powered logo detection and audience reach data to measure the real commercial impact of sponsors in women’s football.
The aim is to prove the financial value of investing in women’s clubs and players by showing how much brand exposure they deliver — in pounds, seconds, and moments that matter.

## Background

Many women’s football clubs and players are undervalued by sponsors due to the lack of clear data portraying the actual exposure they deliver. For instance, a 2019 Brand Finance study estimated that women’s football sponsorship is undervalued by over US$1bn globally. Further undervaluation comes from a 2023 FIFPro survey where 29% of women players in FIFA Women’s World Cup qualifiers or UEFA Women’s Euros qualifiers were not paid at all, and 66% reported taking unpaid or paid leave from other jobs to compete. Considering the continuous clear pattern, that the women’s game is exploding not only in viewership numbers but also from a financial standpoint. There is commercial growth and maturity of the women’s game – 2025 Women’s Euro projected to generate a record-breaking €32.5million in sponsorship revenue – this is more than double of the €15.3million generated in 2022. The return of investment from sponsoring women’s sport can be high too – UK’s Office for Women in Sport and Recreation found that for every $1 invested, sponsors of elite women's sport receive an average return of $7.29 in customer value. This project is using AI, not just a tech tool, but a tool of fairness ensuring players and women’s club receive the commercial recognition they deserve.


![Image](https://github.com/user-attachments/assets/0e313687-cf10-43ad-8127-898b1b6d6d8e)



## How is it used?

My project would be used in the sport sponsorship/marketing world in the women’s football game. The main clients would be clubs who would use the model to generate AI-driven reports showing sponsors the commercial impact of women’s football, and so helping them secure more lucrative deals. Players themselves could use this to prove their own commercial value when it comes to their own personal branding. It would give players a leverage in sponsorship negotiations. Further, sponsors could utilise this project as they can track the real return on their sponsorship. Ultimately, fans would, indirectly, benefit from increased investment in women’s game. The ideal would be: Match footage &rarr; AI analysis &rarr; Insights &rarr; Actions for each stakeholder.


## Data and AI Methods

This project depends on primarily on match footage from broadcasters, match highlights, and social media clips where sponsor logos are visible. Further data sources can include club press images and social media posts to capture sponsor exposure outside the pitch. The quality of the data would generally be quite high, considering broadcasters are captured in high definition. However, accessibility may be an issue considering I may need access to rights-protected footage from clubs and leagues.

AI techniques for this project would utilise sports event data, video and logo detection , and machine learning. I would need to collect to collect videos clips from football matches, from highlights, full-match recordings, and social media clips). A dataset of sponsor logos that appear on kits, pitch boards, or interview backdrops. Match event data from public APIs such as Football-Data.org. Engagement data from social media APIs to track clips. I would then need to use a computer vision API to scan frames of match clips, identify how often sponsor logos appear. Tagging each appearance with a goal, reply, or general play. This would show not only how often a sponsor appears, but in what moment. A classification model would treat whether a sponsor appearance would be ‘high-value’ or ‘low-value’ For instance, a sponsor appearing in a last-minute goal celebration would be ‘high-value’. A regression model could estimate how logo visibility relates to fan engagement via views, likes and shares. A deep learning algorithm such as a convolutional neural network (CNNs) could identify sponsor logos accurately. Combining all this could produce an exposure score that combines frequency, duration, and emotional context of sponsor visibility. This model could be trained to a point where it could be used in live matches where clubs and sponsors could see the ROI of their partnership in real-time.


## Challenges


Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)


## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 

```
## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
