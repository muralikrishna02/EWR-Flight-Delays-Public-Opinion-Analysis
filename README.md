# EWR-Flight-Delays-Public-Opinion-Analysis
Explore EWR Airport flight delays, identify causes like traffic management and capacity constraints, and propose enhancements in infrastructure, staffing, and technology to improve operations and passenger experience.


# EWR Airport Flight Delays and Public Sentiment Analysis

## Abstract

EWR (Newark Liberty International Airport) faced significant delays in 2022, resulting in growing public dissatisfaction and criticism. This project conducts a multi-faceted analysis, examining delay factors and public sentiment related to EWR Airport.

## Introduction

Newark Liberty International Airport (EWR), a major airport in New Jersey serving the New York City metropolitan area, has witnessed a substantial increase in flight delays. This has led to frustration among passengers and airlines, with EWR ranking poorly in terms of flight delays in the United States (Federal Aviation Administration, 2023). In 2022, flight delays at EWR surged by over 50% compared to the previous year, negatively impacting airlines and passenger satisfaction.

The reasons for these delays are multifaceted, including air traffic congestion, runway closures, weather-related disruptions, and operational challenges. For instance, the summer of 2022 saw record thunderstorms that disrupted flight schedules.

To address this issue, airport operators and airlines are working to identify primary delay causes and implement strategies for operational improvements, such as optimizing runway usage and enhancing communication during disruptions.

This project aims to investigate the causes of delays at EWR and assess public sentiment toward the airport. We will analyze flight data and social media posts, offering insights into delay causes and recommendations for operational enhancements. The research also delves into the impact of public sentiment on an airport's reputation and the role of social media in shaping public perception.

## Repository Contents

- **Data**: This folder contains datasets used in the analysis.
- **Notebooks**: Jupyter notebooks with code for data analysis and sentiment analysis.
- **Sentiment analysis**: Jupyter notebook with code forsentiment analysis.
- **Visualisation.md**: Visualisations are shown in this .

## Insights from the Dataset

The data consists of various metrics to assess airlines' performance regarding their flights' timeliness. These metrics include:

- **Scheduled Departures and Arrivals**: The number of flights scheduled for departure and arrival.
- **On-Time Departures and Arrivals**: The percentage of flights departing and arriving within 15 minutes of their scheduled times.
- **Gate Departure and Arrival Delays**: The average delay in departing and arriving at the gate.
- **Taxi Times**: The average time spent taxiing on the runway.
- **Airport and Airborne Delays**: The average time spent waiting on the ground and in the air before takeoff.
- **Taxi In Delay**: The time flights wait to park at the gate after landing.
- **Block Delay**: The time flights wait for a gate to become available.
- **Gate Arrival Delay**: The time flights wait at the gate after landing.

These metrics provide valuable insights into an airline's performance and can be used to identify areas for improvement. High values for these metrics may indicate issues with airport congestion, weather, or operational inefficiencies.



## Usage

Follow the instructions in the Jupyter notebooks in the `notebooks` folder to explore the analysis, findings, and recommendations.

## Algorithm: Latent Dirichlet Allocation (LDA)

LDA (Latent Dirichlet Allocation) is a machine learning algorithm commonly used in natural language processing to identify topics within a corpus of text data. It works by recognizing patterns in the co-occurrence of words in documents and clustering those patterns into topics.

In analyzing airport delay data, LDA can be useful for identifying the underlying topics or causes of delays. For example, suppose we have a corpus of text data consisting of reports on airport delays. In that case, LDA can help us identify the most common topics or causes of delays by clustering related words and phrases into distinct topics.

By using LDA, we can gain insights into the primary causes of delays at an airport and develop targeted solutions to address them. This analysis can help improve operational efficiency and the passenger experience.


## Sentiment Analysis

We have also performed sentiment analysis on the tweets from Twitter to understand public opinion about EWR airport. We have collected over 2100 tweets from Twitter with search terms including ‘EWR delay’, ’EWR baggage claim’, and ‘EWR weather’. We found that around 59.7% of tweets are negative, indicating that people face delays issues at EWR airport.

## Results

The key findings and recommendations based on the analysis of flight delays and public sentiment at EWR Airport:

**Key Findings:**

1. **Primary Causes of Flight Delays:** The analysis identified several primary causes of flight delays at EWR Airport. These include "Traffic Management Initiatives," "Gate Delays," "Taxi Delays," and "Airborne Delays." These delays can be attributed to factors like airport capacity constraints, operational inefficiencies, and high traffic volume.

2. **Impact of Capacity Constraints:** The study highlighted the significance of airport capacity constraints as a key contributor to delays. Despite the decrease in arrivals and departures during the COVID-19 pandemic, the airport's capacity remained a challenge, especially in 2022. This suggests the need for infrastructure upgrades and efficient resource management to address delays.

3. **Public Sentiment:** Sentiment analysis of Twitter data revealed that around 59.7% of tweets expressed negative sentiment related to EWR Airport. The most discussed delay topics in tweets were "Traffic Management Initiatives," "Gate Delays," and "Taxi Delays," which aligns with the identified delay causes in the analysis.

**Recommendations:**

1. **Invest in Infrastructure Upgrades:** To mitigate delays caused by capacity constraints, EWR Airport should consider investing in infrastructure upgrades, such as expanding runways and gate facilities. This will help the airport handle increased traffic more efficiently.

2. **Enhance Staffing Levels:** Addressing delays also requires maintaining adequate staffing levels. Considering the impact of reduced staff post-COVID, EWR should evaluate staffing needs and ensure that there are sufficient personnel to handle flights, passengers, and baggage.

3. **Traffic Management Initiatives:** To manage traffic effectively, the airport should continue implementing and refining traffic management initiatives. This might include optimizing flight schedules and gate usage during peak hours to reduce congestion.

4. **Weather Forecasting Tools:** Given the impact of weather-related delays, EWR should invest in advanced weather forecasting tools to better anticipate adverse weather conditions. This will help the airport proactively adjust operations to minimize disruptions.

5. **Improve Communication:** Enhancing communication between airlines and passengers during disruptions is crucial. EWR should establish effective communication channels to keep travelers informed about delays and provide alternative solutions.

6. **Social Media Engagement:** EWR can use social media platforms to engage with the public, respond to complaints, and provide real-time updates during delays. This proactive approach can help manage public sentiment and improve the passenger experience.

7. **Data-Driven Decision-Making:** Continue analyzing flight data and public sentiment over time to make informed, data-driven decisions. Regularly assess performance metrics and adjust strategies accordingly.

By implementing these recommendations, EWR Airport can work towards reducing delays, improving operational efficiency, and enhancing the passenger experience. Addressing capacity constraints and public sentiment is key to maintaining a positive reputation and ensuring a smoother travel experience for all.


## Conclusion

In conclusion, the analysis has revealed that many of the delays at EWR are related to "Traffic management initiatives", "Gate delays", "Taxi delays", and "Airborne delays". This analysis has been done, including the pre and post-Covid period, providing a good picture of how Covid-19 has affected air traffic.

We also analyzed that the rise in delays at EWR airport will go back to the pre-Covid level. These delays can occur due to capacity constraints, which can arise when there is insufficient infrastructure, staff, or resources to handle the volume of flights and passengers. As a result, airports need to monitor and address these delays to improve their operational performance and reduce passenger frustration.

Addressing capacity constraints may involve investing in infrastructure upgrades, increasing staffing levels, and implementing new technologies and procedures. By taking proactive measures to address these issues, airports such as EWR can improve their operational efficiency and provide a better travel experience for passengers.
