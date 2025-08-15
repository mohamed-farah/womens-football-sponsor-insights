# womens-football-sponsor-insights

Final project for the Building AI course

## Summary

This project uses AI-powered logo detection and audience reach data to measure the real commercial impact of sponsors in women’s football.
The aim is to prove the financial value of investing in women’s clubs and players by showing how much brand exposure they deliver — in pounds, seconds, and moments that matter.



## Background

Many women’s football clubs and players are undervalued by sponsors due to the lack of clear data portraying the actual exposure they deliver. For instance, a 2019 Brand Finance study estimated that women’s football sponsorship is undervalued by over US$1bn globally. Further undervaluation comes from a 2023 FIFPro survey where 29% of women players in FIFA Women’s World Cup qualifiers or UEFA Women’s Euros qualifiers were not paid at all, and 66% reported taking unpaid or paid leave from other jobs to compete. Considering the continuous clear pattern, that the women’s game is exploding not only in viewership numbers but also from a financial standpoint. There is commercial growth and maturity of the women’s game – 2025 Women’s Euro projected to generate a record-breaking €32.5million in sponsorship revenue – this is more than double of the €15.3million generated in 2022. The return of investment from sponsoring women’s sport can be high too – UK’s Office for Women in Sport and Recreation found that for every $1 invested, sponsors of elite women's sport receive an average return of $7.29 in customer value. This project is using AI, not just a tech tool, but a tool of fairness ensuring players and women’s club receive the commercial recognition they deserve.



## How is it used?

This project depends on primarily on match footage from broadcasters, match highlights, and social media clips where sponsor logos are visible. Further data sources can include club press images and social media posts to capture sponsor exposure outside the pitch. The quality of the data would generally be quite high, considering broadcasters are captured in high definition. However, accessibility may be an issue considering I may need access to rights-protected footage from clubs and leagues.

AI techniques for this project would utilise sports event data, video and logo detection , and machine learning. I would need to collect to collect videos clips from football matches, from highlights, full-match recordings, and social media clips). A dataset of sponsor logos that appear on kits, pitch boards, or interview backdrops. Match event data from public APIs such as Football-Data.org. Engagement data from social media APIs to track clips. I would then need to use a computer vision API to scan frames of match clips, identify how often sponsor logos appear. Tagging each appearance with a goal, reply, or general play. This would show not only how often a sponsor appears, but in what moment. A classification model would treat whether a sponsor appearance would be ‘high-value’ or ‘low-value’ For instance, a sponsor appearing in a last-minute goal celebration would be ‘high-value’. A regression model could estimate how logo visibility relates to fan engagement via views, likes and shares. A deep learning algorithm such as a convolutional neural network (CNNs) could identify sponsor logos accurately. Combining all this could produce an exposure score that combines frequency, duration, and emotional context of sponsor visibility. This model could be trained to a point where it could be used in live matches where clubs and sponsors could see the ROI of their partnership in real-time.


Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">


```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
