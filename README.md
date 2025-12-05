Impact of Heatwaves on the Arceye Hawkfish
================
by Tong Ning, Miriam Bergeron, Ryan Gleason, and Moreblessing Banda

## Summary

The study focused on the effect of heatwaves on coral reef fish. The study was conducted by Van Wert et al. and was published on July 15, 2024. The Hawkfish were collected in Mo'orea, French Polynesia in 2019 during the winter and 2022 during the summer. They studied how marine heatwaves impacted the performance and thermal tolerance of the arceye hawkfish, which is a tropical predatory fish. The purpose of our analysis of this study was to understand the impact that heat waves have on arceye hawkfish and their functioning. With that information, we were able to comprehend the relation between ocean temperatures and the performance of arceye hawkfish, and theorize the larger impact of climate change on marine populations. 

## Methods

The researchers used five temperature treatments (27, 28, 29, 31, or 33°C) for one week to test hawkfish’s acclimation ability, which they measured by metabolic performance metrics, including maximum metabolic rate (MMR), standard metabolic rate (SMR), and costs of digestion (specific dynamic action, SDA), using respirometry chambers. A subset of fish and wild fish were tested for thermal tolerance using an acute cardiac thermal tolerance test. The metabolic data were processed in R and the heart rate data were processed in LabChart.

## Analysis

From the boxplot of maximum metabolic rate (MMR) by heatwave treatment, colored by season, the MMR changes with heatwave temperature. MMR is relatively high at 27 °C, drops to its lowest values at 28 °C, then increases at 29 °C, with the highest medians at the strongest heatwave treatments (31–33 °C). At 33 °C, both the median and spread of MMR are highest, indicating that extreme heatwaves are associated with especially high and variable maximum metabolic rates compared with temperatures closer to the normal 27–29 °C range. Season also has an impact on the fish’s MMR, where winter fish at 27 and 31 °C tend to have higher MMR than summer fish at nearby temperatures. In contrast, summer fish during the moderate 28–29 °C heatwaves exhibit the lowest medians and relatively low variabilities, suggesting a more suppressed metabolic capacity. 

These findings suggest that heatwaves can alter hawkfish metabolic demands. In both the coolest (27 °C) and most extreme (31–33 °C) heatwave treatments, fish exhibit higher MMR, indicating they need to allocate more energy to basic physiological maintenance under these conditions. This indicates that increasingly frequent and intense heatwaves are likely to push hawkfish closer to their physiological limits.

The Second Box plot depicts the absolute aerobic scope for fish exposed to heatwave treatments of 27°C, 28°C, 29°C, 31°C, and 33°C, separated by summer (pink) and winter (teal) seasons. Winter fish appear to have a higher aerobic scope compared to the summer fish. This means that they are able to handle the heatwave treatments better because they have more energy during the winter. Hawkfish in the summer are already living close to their thermal limits, so they are not able to deal with the heatwave treatments as well as the winter fish can. The plot also shows that in winter, as the treatment gets harsher, the aerobic scope drops slightly, but is still much higher than any of the summer fish aerobic scopes. We see the opposite pattern in summer, but again, they are still much lower than the winter fish, showing that winter fish handle treatments better. The temperature treatments being different among the seasons is something to note, and if we were to run this study, we would make sure the treatments are the same across seasons, so this analysis would be more conclusive.

The last two line graphs show the relationship between hawkfish body weight and oxygen consumption throughout the year, as well as the effects of summer-time heat stress. The summer panel shows that the fish's capacity to maintain normal physiological performance is limited by high temperatures, as shown by the fast decrease in oxygen use as body weight increases and the lower and more variable total values. The winter panel, on the other hand, has a tighter cluster of dots and a much smoother decrease, suggesting that fish maintain more constant oxygen-use levels in colder climates. All of the trends point to a reduction in hawkfish physiological ability at heatwave-level temperatures, which suggests the idea that summer fish are more stressed by heat than winter fish.
Overall, our plots and results suggest that marine heatwaves make life harder for hawkfish, especially in the summer. At both very cold and hot temperatures, the fish show higher metabolic rates, which means they must spend more energy to stay alive. Winter fish can handle these stressful temperatures better, since they generally have a higher aerobic scope, as confirmed by the line plots. However, because different temperatures were used across seasons, season and temperature are partly confounded, so these seasonal patterns are suggestive and can’t be perceived as a direct influence factor.


## Conclusions

Through our analysis of the Van Wert et al. (2024) study and our plots, we were able to understand the relationship between marine heatwaves and the functioning of hawkfish. The plots reveal at higher temperatures, hawkfish have lower maximum metabolic rates, suggesting that the high temperatures cause the fish to experience thermal stress as a result of expending too much energy. Additionally, hawkfish have lower aerobic scopes at warmer temperatures, meaning they are more strained in the summer than in the winter. Additionally, the maximum metabolic rate of hawkfish differs across body weight and season, as heavier fish have lower maximum metabolic rates, suggesting they are disproportionately impacted by the high temperatures compared to smaller fish. Overall, marine heatwaves significantly restrict the arceye hawkfish’s energy output and performance, posing a great threat to their functioning.

While Van Wert et al. (2024) provided a strong foundation for our project, there were limitations to the conclusions we were able to draw from the data. Because the data was collected in one year, there was not a strong emphasis on the long-term impacts of marine heatwaves on the health of hawkfish, which prevented us from charting the possible deterioration of the fish over time. Additionally, studying the fish over multiple years or decades would have allowed for an analysis of the frequency of heatwaves. Recent research has found that, due to climate change, both the frequency and intensity of marine heatwaves is increasing (Marcos et al., 2025). Thus, we recommend that future research explores the interaction between hawkfish and marine heatwaves over an extended period, to better understand how climate change will continue to harm hawkfish. Additionally, Van Wert et al.’s population of hawkfish lived only in Mo’orea, French Polynesia. Future research could look at the frequency of marine heatwaves across the globe, to identify areas that have usually high frequencies of heatwaves, to understand how different populations of marine animals will be affected by heatwaves.


## Handout

Our handout can be found [here](handout/Handout.pdf).

## Memo

A link to the code and how we created our graphics in our memo can be found [here](memo/memo.md).

## Data

Van Wert, J., Birnie-Gauvin, K., Gallagher, J., Hardison, E., Landfield, K., Burkepile, D., & Eliason, E. (2024). Despite plasticity, heatwaves are costly for a coral reef fish [Data set]. Dryad. Retrieved October 23, 2025, from https://doi.org/10.5061/dryad.wdbrv15vm


## References

Marcos, M., Amores, A., Agulles, M., Robson, J., & Feng, X. (2025). Global warming drives a threefold increase in persistence and 1 °C rise in intensity of marine heatwaves. Proceedings of the National Academy of Sciences of the United States of America, 122(16), e2413505122. https://doi.org/10.1073/pnas.2413505122

Van Wert, J., Birnie-Gauvin, K., Gallagher, J., Hardison, E., Landfield, K., Burkepile, D., & Eliason, E. (2024). Despite plasticity, heatwaves are costly for a coral reef fish [Data set]. Dryad. Retrieved October 23, 2025, from https://doi.org/10.5061/dryad.wdbrv15vm

