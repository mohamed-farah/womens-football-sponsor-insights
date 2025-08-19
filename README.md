# womens-football-sponsor-insights

Final project for the Elements of AI Course.

## Summary

This project uses AI-powered logo detection and audience reach data to measure the real commercial impact of sponsors in women’s football.
The aim is to prove the financial value of investing in women’s clubs and players by showing how much brand exposure they deliver — in pounds, seconds, and moments that matter.

## Background

Many women’s football clubs and players are undervalued by sponsors due to the lack of clear data portraying the actual exposure they deliver. For instance, a 2019 Brand Finance study estimated that women’s football sponsorship is undervalued by over US$1bn globally. Undervaluation comes from a 2023 FIFPro survey where 29% of women players in the FIFA Women’s World Cup qualifiers or UEFA Women’s Euros qualifiers were not paid at all, and 66% reported taking unpaid or paid leave from other jobs to compete. Further, there is a clear pattern that the women’s game is exploding not only in viewership but seeing commercial growth and maturity. The 2025 Women’s Euro projected to generate a record-breaking €32.5million in sponsorship revenue, this is more than double of the €15.3million generated in 2022. The return of investment from sponsoring women’s sport can be high too – UK’s Office for Women in Sport and Recreation found that for every $1 invested, sponsors of elite women's sport receive an average return of $7.29 in customer value. This project is using AI, not just a tech tool, but a tool of fairness ensuring players and women’s club receive the commercial recognition they deserve.


![Image](https://github.com/user-attachments/assets/0e313687-cf10-43ad-8127-898b1b6d6d8e)



## How is it used?

My project would be used in the sport analytics world in the women’s football game. The main clients would be clubs who would use the model to generate AI-driven reports showing sponsors the commercial impact of the game, and so helping them secure more lucrative deals. Players themselves could use this to prove their own commercial value when it comes to their own personal branding, providing players with leverage in sponsorship negotiations. Further, sponsors could utilise this project as they can track the real return on their sponsorships. Ultimately, fans would, indirectly, benefit from increased investment in women’s game.

The ideal model would be: **Match footage &rarr; AI analysis &rarr; Insights &rarr; Actions for each stakeholder.**


## Data and AI Methods

This project depends on primarily on match footage from broadcasters, match highlights, and social media clips where sponsor logos are visible. Further data sources can include club press images and social media posts to capture sponsor exposure outside the pitch. The quality of the data would generally be quite high, considering broadcasted games and photography are captured in high definition. However, accessibility may be an issue considering I may need access to rights-protected footage from broadcasting networks and leagues.

AI techniques for this project would utilise sports event data, video and logo detection, and machine learning. I would need to collect videos clips from full-match recordings, highlights, and social media. A dataset of sponsor logos that appear on kits, pitch boards, or interview backdrops. Match event data from public APIs such as [Opta by Stats Perform API](https://www.statsperform.com/opta/). Engagement data from social media APIs such as [Twitter API](https://developer.twitter.com/en/docs) and [Instagram Graph API](https://developers.facebook.com/products/instagram/apis/). I would then need to use a computer vision API to scan frames of match clips, identify how often sponsor logos appear using [Google Cloud Vision API](https://cloud.google.com/vision), tagging each appearance with a goal, reply, or general play. This would show not only how often a sponsor appears, but in what moment. A classification model would treat whether a sponsor appearance would be ‘high-value’ or ‘low-value’. For instance, a sponsor appearing in a last-minute goal celebration would be associated with a ‘high-value’ moment. A regression model could estimate how logo visibility relates to fan engagement via views, likes and shares. A deep learning algorithm such as a convolutional neural network (CNNs) could identify sponsor logos accurately. Combining all this could produce an exposure score that combines frequency, duration, and emotional context of sponsor visibility. This model could be trained to a point where it could be used in live matches where clubs and sponsors could see the ROI of their partnership in real-time.


## Challenges

This project does not guarantee increased visibility of sponsors will lead to more lucrative sponsorships deals; it only provides data to support negotiations. It also does not address all variables that influence sponsorship value such as brand alignment and off-field player influence. Another challenge could be measuring the emotional impact of sponsorship exposure, when it comes to what is considered a ‘low-value’ and ‘high-value’ moment.

A limitation to consider is how accessible the data is. As mentioned, full-match replays are not always publicly available so I would need permission to obtain this from broadcasters such as Sky Sports and the BBC. Another limitation would be how accurate would the logo detection be considering that football games are fast paced, so would an image detector be affected by motion blur or lighting.
An ethical consideration would be about transparency. Stakeholders should clearly understand how the AI measures ‘value’ and how it comes to its decisions.


## What Next?

This project could grow into a comprehensive sponsorship intelligence platform for women’s football. In the future it could integrate predictive analytics to forecast sponsorship value for upcoming tournaments, helping clubs and players proactively pitch to brands.

A big player in this field is ‘Nielsen Sports’ who are an seen as leaders for sponsorship valuation. They work with major rights holders and provide media valuation reports for sponsors. Whilst they cover a large range of sport, my project would focus specifically for the women’s game, where there is a clear gap in sponsorship analytics. My project would also provide a more open, data-driven approach that would be accessible to smaller clubs and leagues.

To move forward in this project, it would require the technical skills in creating a model which could comprehensively produce useful insights in the reach of women’s football. It would require data partnerships to access official broadcast footage. Design and UX skills would prove useful in creating dashboards and reports that stakeholders can easily navigate and understand.




![Image](https://github.com/user-attachments/assets/641ea537-1e0c-4b4c-a209-5d160a221fd3)


## Acknowledgments

- [Brand Finance 2023](https://brandfinance.com/press-releases/total-potential-of-womens-football-sponsorship-undervalued-by-over-us1-billion) – Total potential of women’s football sponsorship undervalued by over US$1 billion.

- [Ampere Analysis via Inside World Football (2025)](https://www.insideworldfootball.com/2025/06/26/uefa-womens-euro-2025-course-double-sponsorship-revenues) – UEFA Women’s Euro 2025 projected to generate at least €32.5 million in sponsorship revenue, more than double the €15.3 million of 2022.

- [The Office for Women in Sport and Recreation (2024), summarised by SPORTFIVE](https://sportfive.us/beyond-the-match/insights/the-commercialisation-of-womens-football) – Every $1 invested in women’s sports generates an average of $7.29 in customer value return.

- [FIFPRO (2023), via Wikipedia summary](https://en.wikipedia.org/wiki/Labour_relations_in_women%27s_association_football) – 29% of women players were not paid for World Cup qualifying, and 66% had to take unpaid leave from other jobs to compete.


- [Aitana Bonmati Press Conference during the 2025 Women's Euro in Switzerland by Florencia Tan Jun](https://media.gettyimages.com/id/2225631565/photo/bern-switzerland-aitana-bonmati-of-spain-speaks-to-the-media-during-the-spain-press.jpg?s=612x612&w=gi&k=20&c=D-6L_3zeUmBrcsaa7_rMsI79yxq9gQsZWljscTA_wpM=)

- [Barcelona lifting the Women's Champions League Trophy 2024](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwgno.com%2Fsports%2Fap-sports%2Fap-uefa-celebrates-growth-of-womens-soccer-as-barcelona-lifts-another-womens-champions-league-trophy%2F&psig=AOvVaw3TWbUMRRkZg2flATZuThVd&ust=1755427346795000&source=images&cd=vfe&opi=89978449&ved=0CBYQjRxqFwoTCNjLgc2Sj48DFQAAAAAdAAAAABBU)
