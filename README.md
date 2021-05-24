# NY CitiBike with Tableau

## Tableau Public

**You can see a live version of this analysis on Tableau Public: [Tableau Public link to Visualization/Story](https://public.tableau.com/profile/shaun.coulter#!/vizhome/Module14-NYCCitibike_16216171699220/NYCCitiBikeStory)**

## Challenge - Overview

For this module we were introduces to Tableau, an industry-leading data visualization application. We were supplied with a dataset of bicycle trips from the NYC service CitiBike - a bicycle sharing program based in New York. This dataset contained all the trips taken place in August 2019 and included a breakdown of the users and the trip lengths. We were tasked with analysing the data and presenting our findings using data visualizations built in Tableau.

The background behind the challenge is to determine whether this similar service could be deployed in Des Moines, Iowa. We would use our visualizations as well as some higher-level analysis to produce a Tableau story from the data and report our findings. We would also be required to suggest further analysis that should be undertaken should a company wish to supply this service.

We use a variety of visualizations in this module, including bar charts, pie charts and heatmaps. We also saved the story compiled from our worksheets to Tableau public, the link of which can be found above. A detailed discussion of our story follows in the results section.

## Challenge - Results

![NYC CitiBike Tableau Story Points](images/0_story_points.png)

These are our city story points, organized by their graph names, they include the 5 challenge charts and 3 picked from the module to tell a story about the NYC CitiBike dataset from August 2019.

![Average Checkout Times for Users](images/1_checkout_times.png)

***Challenge Graph*** - **Average Checkout Times for Users**: The average (in this case, mode) length of a bike rental/trip duration is for a 4-6-minute journey. This would imply that in NYC there were an abundance of places to travel to that are nearby to each other - this includes workplaces and housing/apartments. In more spaced-out metropolitan areas, you could expect to see the trip duration increase until it became infeasible to use a bike rather than a car, i.e., more suburban areas. New York City is well known for its dense population and high traffic so short trips on a bike are plentiful.

![Gender Breakdown](images/2_gender_breakdown.png)

***Module Graph*** - **Gender Breakdown Pie Chart**: Here we see a pie chart representing the gender breakdown of bike users. Around two thirds of the users are male, a quarter are female, and roughly nine percent are unknown. This shows the CitiBike service is mainly dominated by male users.

![Checkout Times by Gender](images/3_gender_checkout.png)

***Challenge Graph*** - **Checkout Times by Gender**: Here we see essentially the first two graphs combined. We see the same male dominance in bicycle usage, but also the same peak trip durations for both genders of 4-6-minutes - so, the length of the journeys is not gender dependent. The unknown gender category does not have such a defined peak, with the more popular trip durations anywhere between 8-30 minutes.

![Customer Subscriber Breakdown](images/4_customer_breakdown.png)

***Module Graph*** - **Customer/Subscriber Breakdown**: This graph shows the breakdown of user type, where subscriber refers to a user with an annual subscription to the service, and customers are those with 1-3-day passes to the service. Subscribers make up 80+% of CitiBike users, this would imply that most of the users are residents of NYC rather than tourists, as tourists have little need to purchase a year-long membership. Given this knowledge and the fact that most journeys are 4-6-minutes we can begin to see CitiBike is mostly being used for work commutes.

![Peak Usage Hours (Trip Start Time)](images/5_peak_hours.png)

***Module Graph*** - **Peak Usage Hours (Using Trip Start Time)**: Following on from our previous hypothesis about CitiBike usage and work commuting we look to this chart that we produced during the module. Quite clearly, we can see that the peak usage times of the service are during so-called rush-hour timeslots: 7-9am and 5-7pm. This trend really solidifies the idea that most users of the service are annual subscribers that use the service for their commute to work.

![Trips by Weekday per Hour](images/6_trips_weekday_hour.png)

***Challenge Graph*** - **Trips by Weekday per Hour**: Here we look at a heatmap style chart that separates the bike usage down by hour of the day, and by day of the week. The darker tones represent the higher usage, and we can see more proof that there is peak usage during rush-hour times on the weekdays, but more spread-out usage on the weekends. We would need to view this data by user type to see how if each type of user is following our hypothesized pattern. We also notice that Wednesday evening rush-hour is not as intense as the other weekdays *(more on this later)*.

![Trips by Gender (Weekday per Hour)](images/7_trips_gender_weekday_hour.png)

***Challenge Graph*** - **Trips by Gender (Weekday per Hour)**: We dissect the heatmap further, first by looking at the data split by gender. We notice, like in the first few charts, that the gender makeup follows the combined data - there is no gender difference in the most popular usage times (rush hours and spread out on weekends). One interesting thing to note is that the unknown gender category does not seem to focus as heavily on the weekday rush-hours, but rather on the spread-out weekend usage. This shows that the majority of unknown-gender users are brief customers (1–3-day passes). This follows from the idea that users would be more comfortable handing over personal data about themselves (like gender) if they are subscribing for a year to a service.

![User Type Trips by Gender by Weekday](images/8_trips_gender_customer_weekday.png)

***Challenge Graph*** - **User Type Trips by Gender by Weekday**: We mention above the need to split the heatmap by user type, and for the final chart of the assignment we do just that. The split by user type shows that the subscribers use the service more during weekdays, while the customers use it more on the weekends. This would be tourists and

## Challenge - Summary

Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.
There is a high-level summary of the results and two additional visualizations are suggested for future analysis.

## Context

This is the result of Module 14 of the University of Toronto School of Continuing Studies Data Analysis Bootcamp Course - **Ny CitiBike with Tableau** - Analysing a NY CitiBike dataset with Tableau. Following the guidance of the module we end up pushing this selection of files to GitHub.
