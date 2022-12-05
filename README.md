# Bellabeat Case Study

[Coursera's](https://www.coursera.org/) [Capstone Project for the Google Data Analytics Certificate](https://www.coursera.org/professional-certificates/google-data-analytics?utm_source=gg&utm_medium=sem&utm_campaign=15-GoogleDataAnalytics-US&utm_content=B2C&campaignid=12504215975&adgroupid=122709142687&device=c&keyword=coursera%20data%20analytics%20course&matchtype=b&network=g&devicemodel=&adpostion=&creativeid=504570191916&hide_mobile_promo&gclid=Cj0KCQjw94WZBhDtARIsAKxWG--aGc_mpu7WTeU8sHtAVT4D9k79qOSJOCdgcl3hVUqPH2zR1B2j8acaAovsEALw_wcB)

## Scenario

A data analyst is working on the marketing analyst team at [Bellabeat](https://bellabeat.com/), a high-tech manufacturer of health-focused products for women. Co-founder, Urška Sršen, believes that analyzing smart device fitness data could help unlock new growth opportunities for the company. The data analyst is asked to focus on one of Bellabeat's products and analyze smart device data to gain insight into how consumers are using their smart devices.

## Business Task

Determine how fitness smart device trends can help influence Bellabeat's marketing strategy for a Bellabeat consumer product.

## Data

Data was retrieved from [FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit) posted by [Mobius](https://www.kaggle.com/arashnic) on [Kaggle.com](https://www.kaggle.com/). This data set contains personal fitness tracker information from 33 FitBit users and is stored in long format. There are some limitations to the data in that the collection is third-party data; it is for less than one month of activity from 2016, which is quite outdated; and it is far from comprehensive with a limited user base of 33 individuals. Its reliability is therefore, questionable. Even though [Mobius](https://www.kaggle.com/arashnic) cites the origin of the data, this does not do much to improve its credibility. Still, I used it as instructed to gather insights in a quest to address the business task.

## Summary

Data were used to show that FitBit users are able to gather data from their fitness devices related to their health and fitness goals. As total daily activity and daily steps increase, their number of calories burned for that day increases. Consumers can therefore use fitness devices at any point to find out if they have met their daily goals or if this is a night to go to the gym or take a trip to the park.

## Visualizations

**Scatterplots and regressions lines**\
Calories burned compared to activity intensity:\
We can see from each scatter plot that as the intensity and duration of activity both increase, the higher the correlation between the activity intensity and the number of calories burned, and the greater the slope of the regression line. The calories burned with increased sedentary time shows a negative correlation and negative slope. The data show a positive correlation between calories burned and activity time.

Calories burned compared to step count:\
Looking more specifically at calories burned against steps on a given day, we also see a positive correlation and the slope of our regression line is also positive for our scatter plot.

Time asleep compared to daily activity minutes, step count, and time in bed:\
We checked to see if either total_active_minutes or total_steps has a relationship with total_minutes_asleep and it is negligible. We also inspected total_minutes_asleep against total_time_in_bed, as instructed. As we would expect, the data are nearly perfectly linear and have a 0.93 correlation with a regression line slope of 0.87.

**Box-and-Whisker Plots**\
When we break down step count into categories using quartile ranges, we can see that each quartile has a higher minimum, q1, median, q3, and maximum calorie burn than the previous quartile with fewer steps that day.

## Marketing Strategy Recommendations

**Bellabeat Leaf - You won't leave home without it.**

1.  Results speak! Staying active during the day, including a high step count, increases calorie burn. The longer an individual is sedentary, the lower their calorie burn. The more active they are, the higher their calorie burn. Busy women need a fitness tracker that is out of mind, but getting the job done. Bellabeat Leaf is one less thing to think about and your tracking information is always there when you need it. As the day goes on, find out if you have met your goals or if this is a night to go to the gym or take a trip to the park. And you are not reliant on your phone to be with you and/or charged for Leaf to track!\
2.  Fitness meets fashion. Bellabeat Leaf will keep track of all of your activity, including step count, so you can stay on track and motivated to reach your goals. Tracking leads to action and it is happening every moment without you having to think about it. The Bellabeat Leaf is fashionable, hypo-allergenic, waterproof, and has a battery that will last 6 months! You will never have to leave it behind because you literally wear it 24 hours a day and it can be worn on a necklace, bracelet, or can be clipped to your clothing.

## Suggestions

1.  Revisit with more recent data of more users over a longer time period, preferably first party data from Bellabeat users.
2.  If not already implemented, be sure the Bellabeat Leaf app allows users to set goals and that the app sends alerts about progress towards completing them.
3.  If not already implemented, be sure the Bellabeat Leaf app alerts users when their sleep time is less than optimal, if their sleep is interrupted often during the night, or if there sleep quality if otherwise poor. Women want to feel energized when they wake up, so that they can meet their fitness and health goals.

## Resources

[Coursera](https://www.coursera.org/)\
[Google Data Analytics Certificate Course](https://www.coursera.org/professional-certificates/google-data-analytics?utm_source=gg&utm_medium=sem&utm_campaign=15-GoogleDataAnalytics-US&utm_content=B2C&campaignid=12504215975&adgroupid=122709142687&device=c&keyword=coursera%20data%20analytics%20course&matchtype=b&network=g&devicemodel=&adpostion=&creativeid=504570191916&hide_mobile_promo&gclid=Cj0KCQjw94WZBhDtARIsAKxWG--aGc_mpu7WTeU8sHtAVT4D9k79qOSJOCdgcl3hVUqPH2zR1B2j8acaAovsEALw_wcB)\
[Bellabeat](https://bellabeat.com/)\
[FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit)\
[Mobius](https://www.kaggle.com/arashnic)\
[Kaggle](https://www.kaggle.com/)\
[DataViz-Baseball by Bronze Toad](https://github.com/BronzeToad/DataViz-Baseball)
