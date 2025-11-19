# data

Place data file(s) in this folder. Add the dimensions (rows and columns).

Then, include codebooks (variables, and their descriptions) for your data file(s)
using the following format.

## VanWert_etal_2023-hawkfish

This dataset contains 75 cases and 22 variables.

The dataset including the following variables:

1. `hawkfish_no` = unique fish ID

2. `year` = year of fish collection and measurements

3. `season` = Austral summer (summer) or Austral winter (winter)

4. `treatment_new` = acclimation temperature; 'wild' indicates fish were not acclimated and were collected from the wild and immediately tested

5. `bw_g` = wet mass of fish (units g)

6. `tank` = fish tank ID during acclimation

7. `tl_cm` = total length of fish (units cm)

8. `sl_cm` = standard length of fish (units cm)

9. `chase_pre_v_post` = whether exhaustive exercise chase occurred before (pre) or after (post) SMR measurements

10. `mmr_corrected` = body mass corrected maximum metabolic rate by universal metabolic scaling coefficient of 0.89 (units mg O2 kg-1 min-1)

11. `smr_low10_all` = standard metabolic rate (units mg O2 kg-1 min-1)

12. `aas_corrected` = absolute aerobic scope (units mg O2 kg-1 min-1)

13. `fas` = factorial aerobic scope calculated as mmr/smr (unitless)

14. `percent_bw_scallop_fed` = percent of body weight scallop fed for SDA trial

15. `SDA_integrated` = integral of specific dynamic action (SDA) (units mg O2 kg-1)

16. `SDA_duration` = duration of specific dynamic action (SDA) (units hours)

17. `peak_SDA_max` = maximum metabolic oxygen consumption (MO2) reached during specific dynamic action (SDA) (units mg O2 kg-1 min-1)

18. `time_peak_SDA_max` = time at which peak_SDA_max occurred (units hours)

19. `sda_coeff` = specific dynamic action (SDA) coefficient (units %)

20. `tarr` = temperature of arrhythmia (units degC), only measured during winter tests

21. `fhmax_peak` = peak maximum heart rate (units beats per min), only measured during winter tests

22. `tpeak` = temperature at which fhmax_peak occurred (units degC), only measured during winter tests
