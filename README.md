# Effect-of-photoperiod-on-aquatic-beetle-behavior
# Differences in Photoperiod Determine Dispersal, Burial, and Perching Behaviors in Aquatic Beetle Peltodytes Callosus (Coleoptera: Haliplidae)

## Noelle Tanaka, Kate S. Boersma 

# Abstract 

Light pollution, an increasing environmental concern, disrupts natural light cycles and has profound effects on the behavior and ecology of aquatic insects. This study examined the direct effects of photoperiod, the duration of daily light exposure, on the dispersal, burial, and perching behaviors of Haliplus punctatus aquatic beetles under controlled laboratory conditions. Beetles were exposed to five distinct photoperiod treatments while temperature and humidity were held constant, and their behaviors were systematically recorded. Statistical analyses revealed no significant associations between photoperiod and most behavioral outcomes, including dispersal, burial, and perching, suggesting that light duration alone does not strongly regulate these behaviors when other environmental factors are controlled. However, survival analysis indicated that beetles exposed to constant light (24-hour photoperiod) dispersed at a significantly lower rate compared to those under a standard 12-hour cycle, highlighting a nuanced behavioral response to uninterrupted light. These findings suggest that while photoperiod may play a limited role in shaping certain behaviors in isolation, aquatic beetles likely integrate multiple environmental cues for behavioral decision-making, warranting further research into the interplay of light and other ecological factors.

Keywords: Haliplidae. Photoperiod. Dispersal. Burial. Perching

# 

# Introduction

Biological rhythms, which are adapted to environmental light cycles, are the most fundamental of all life's adaptations. Just as exposure to artificial light at night can disrupt human circadian rhythms and sleep patterns, light pollution fundamentally alters natural light cycles for wildlife; for example, it can disorient migratory birds that rely on seasonal light cues for navigation and timing, illustrating how photoperiod, the cycle of light and dark in a 24-hour day, is a critical regulator of physiological activities and behaviors across diverse taxa.(Cajochen et al., 2004; Krishnan & Lyons, 2015). These behaviors have developed over time in response to predictable environmental events, thereby maximizing the chances of survival or reproductive fitness.   
In aquatic ecosystems, photoperiodic cues are essential for organisms that shift between aquatic and terrestrial environments. Aquatic insects, which comprise a substantial portion of freshwater biodiversity, have developed highly complex and effective means to recognize and utilize light patterns for foraging, dispersal, and predator evasion (Horváth & Csabai, 2014). Among organisms, the Coleoptera is one of the most diverse groups, with over 13,000 described species inhabiting freshwater habitats worldwide.  
Studies have recently shown that several aquatic beetles possess a specialized "polarization vision" system that enables them to use polarized light reflected from water surfaces to orient themselves toward aquatic habitats. This system, referred to as a "polarization sun-dial" (Csabai et al., 2006; Bernáth et al., 2004), is essential for behaviors such as dispersal flight, where aquatic beetles must detect the water surface while flying above it. It has been reported that aquatic beetles show bimodal flight activity at distinct times of the day (Csabai et al., 2006; Boda & Csabai, 2009). The periods with the highest diel flight activity for aquatic beetles are mid-morning, noon, and evening, when polarized light is highest and accurate water-surface detection from the air is enhanced.  
Aquatic beetles exhibit complex seasonal photoperiodic responses and display diverse dispersal patterns across species. These patterns include drought escape flights in summer and initiation flights for habitat colonization in spring and fall (Miguélez & Valladares, 2008; Boda & Csabai, 2013). Along with photoperiod, temperature, and precipitation, these factors likely interact with the photoperiodic response to temper the dispersal rates or behaviors of these species. This suggests beetles may integrate multiple environmental signals to prepare for appropriate dispersal (Guppy, 1982; Iversen et al., 2017).  
While there is an increasing appreciation for the potential photoperiodic components driving aquatic beetle behavior, studies published to date have reached their conclusions based on field-based observational studies that have not isolated the effects of light cycles from environmental factors, such as temperature, humidity, and predator pressure. Field studies provide ecological evidence of the influences on the studied species; however, a connection between photoperiodic cycles and behavior has not been conclusively established, which represents a significant shortcoming in the mechanistic understanding of how light cycles regulate basic behaviors in aquatic beetles.  
Three notable behaviors in aquatic beetles—dispersal, burial, and perching—are widely considered to be photoperiod-dependent; however, their specific responses to variations in the light regime have not been systematically studied. Dispersal, the movement of individuals among habitats, is essential for population dynamics and genetic connectivity. Burial, defined as the process of burrowing into sediment, serves both protective and foraging functions. Perching, observed when beetles rest on surfaces above the water, may facilitate respiration, thermoregulation, and predator avoidance. Understanding how photoperiod directly influences these behaviors is crucial for predicting aquatic beetles' responses to environmental change and for informing management and conservation strategies. This study addresses the research question: How does photoperiod directly affect dispersal, burial, and perching behaviors in aquatic beetles when environmental variables are experimentally controlled? It is hypothesized that aquatic beetles will exhibit distinct behavioral responses to different photoperiod treatments, with dispersal activity peaking during simulated dawn and dusk, burial increasing during extended dark phases, and perching frequency varying with light-dark transitions, independent of other environmental factors.

# Materials and Methods:

## Study Organisms:

In June 2024, Haliplus punctatus beetles were collected from intermittent stream habitats in Corte Madera Pond, San Diego County, California, using a fine mesh D-net. At the time of collection, water temperature was 23.9°C, dissolved oxygen measured 5.1 mg/L, pH was 7.68, and conductivity was 704 μS/cm. Benthic sediment was gathered from a depth of 0.5 m, filtered through a 1 mm mesh to remove fine particles, and desiccated at 95°C for 24 hours before storage. In the laboratory, beetles were maintained in dechlorinated tap water at 14°C and fed brine shrimp; water changes were performed weekly until the start of the experiment.

## Experimental Design:

We assessed the effects of photoperiod on Haliplus punctatus behavior using a factorial design with five light treatments: 0, 8, 12, 16, and 24 hours of LED exposure per day, controlled by programmable timers. All the treatments consisted of a 60-watt LED light bulb, which emitted on average about 16.95 µmol m⁻² s⁻¹ of photosynthetically active radiation (PPFD), with a spectral peak at 453 nm (23.73 mW m⁻²) and a balanced output across the blue (3.45 µmol m⁻² s⁻¹), green (7.08 µmol m⁻² s⁻¹), and red (6.42 µmol m⁻² s⁻¹) wavelength ranges. Each treatment group consisted of 20 individually housed beetles, with experimental units constructed from a nested cup system: a smaller inner cup (containing 1.2 mL of sediment, 30 mL of water, and a 3.8 cm wooden dowel perch) placed within a larger outer cup holding 14.8 mL of water. All units were covered with 1 mm mesh and secured with rubber bands to prevent escape while allowing air exchange. In total, 100 experimental units were randomly assigned numbers 1–100, and beetles were randomly allocated to each unit; five additional units without beetles were used for temperature monitoring. To eliminate confounding variables, all external light sources were excluded during the experiment. Behavioral observations were conducted daily at 10:00 AM and 4:00 PM for six consecutive days using a standardized ethogram, scoring dispersal (presence in the outer cup), burial (absence from view, requiring sediment disturbance), and perching (positioning on the dowel above or below the water surface). Temperature and humidity were recorded daily for each treatment group using a thermometer and a mini hydrometer.   
![][image1]  
Image 1: The cups used for each beetle in the experiment, measurements are in inches. 

## Analysis:

All data analyses were conducted in R using the tidyverse suite of packages. Raw experimental data were imported from CSV files, and categorical variables—including photoperiod, light status, dispersal, burial, and perching behaviors—were recoded to labeled factors (“Yes”/“No”; “On”/“Off”) to enhance interpretability. Numeric summaries and the structure of the cleaned dataset were examined to identify irregularities and missing values, with replicate and identification variables retained for traceability throughout the analysis.

Associations between photoperiod treatments and categorical behavioral outcomes (dispersal, burial, and perching) were assessed using chi-square tests of independence, with a focus on Day 3 data. Mosaic plots generated with ggplot2 visualized the proportion of individuals exhibiting each behavior across treatments. Assumptions for chi-square tests—including sample size, independence, and minimum expected cell frequencies—were checked, and Fisher’s Exact Test was used if assumptions were violated. Cramér’s V was calculated to estimate effect sizes for significant associations.

Survival data for dispersal events were analyzed using the Cox proportional hazards model, treating photoperiod as a categorical predictor, and model assumptions were assessed using scaled Schoenfeld residuals. Survival curves stratified by photoperiod were plotted, along with confidence intervals, using the survminer package.

Environmental variables, specifically temperature and humidity, were compared across photoperiod treatments using one-way ANOVAs. Assumptions of normality (Shapiro-Wilk test) and homogeneity of variance (Bartlett’s test) were confirmed before analysis, and line plots were generated to illustrate daily trends for each treatment group.

# Results: 

## Dispersal:

Initially, a stacked bar chart was used to visualize the proportion of beetles exhibiting cumulative dispersal (“Yes” or “No”) across the five photoperiod treatments for experimental rows 1102-1201. However, a chi-square test of independence revealed no significant association between photoperiod and dispersal rate (χ²(4, N \= 100\) \= 3.76, p \= 0.439), with all expected cell frequencies above five and a small effect size (V \= 0.194). Given the lack of significance and the limitations of analyzing a single time point, this approach was deemed insufficient for capturing the dynamics of dispersal behavior.

![][image2]

Figure 1: Dispersal Proportions by Photoperiod for Rows 1102–1201, last day of experiment (χ² (4, N \= 100\) \= 3.76, p \= 0.439)

To address this, a survival analysis was conducted using Kaplan-Meier curves to depict the probability of beetles remaining non-dispersed over time for each photoperiod treatment (N \= 1200). This analysis revealed a significant overall effect of photoperiod on dispersal timing (p \= 0.0019), with the 24-hour group exhibiting a significantly lower dispersal hazard. The Cox proportional hazards model confirmed this result, showing a significant overall effect (likelihood ratio test:  X2=17.05, df=4,  p=0.0019), and specifically, beetles in the 24-hour photoperiod group dispersed at a significantly lower rate compared to the 12-hour reference group (hazard ratio \=0.73, p=0.029). The proportional hazards assumption was met (p \= 0.60). Comparisons to the 12-hour photoperiod indicated that the 8-hour group had a marginally higher dispersal rate (1.26 times faster, p \= 0.0733), the 24-hour group had a significantly lower rate (0.73 times slower, p \= 0.0288), and the 0- and 16-hour groups showed no significant difference.

![][image3]

Figure 2: Survival Curves for Dispersal by Photoperiod (likelihood ratio test for 24-hour group:  X2=17.05, df=4,  p=0.0019)

## Burial:

A stacked bar plot was used to display the proportion of beetles observed buried versus not buried across the different photoperiod treatments on Day 3\. Statistical analysis revealed no significant association between photoperiod and burial behavior (χ² (4, N \= 100\) \= 5.51, p \= 0.239), and the effect size was small (V \= 0.235). 

![][image4]

Figure 3: Burial Proportions by Photoperiod on Day 3  (χ² (4, N \= 100\) \= 5.51, p \= 0.239)

## Perching In and Out of Water:

A stacked bar plot was used to illustrate the proportion of beetles perched on a stick in water across the different photoperiod treatments on Day 3\. Statistical analysis revealed no significant association between photoperiod and perching in water (χ2(4, N \= 100\) \= 1.43, p \= 0.839), with a small effect size (V \= 0.120). 

![][image5]

Figure 4: Perched on the Stick in Water by Photoperiod on Day 3 (χ2(4, N \= 100\) \= 1.43, p \= 0.839)

Similarly, a stacked bar chart was generated to represent the proportion of beetles perched on a stick out of water, grouped by photoperiod, on Day 3\. No statistically significant association was found between photoperiod and perching out of water (χ²(4, N \= 100\) \= 4.44, p \= 0.349), and the effect size was also small (V \= 0.211). 

![][image6]

Figure 5: Perched on the Stick out of Water by Photoperiod on Day 3 (χ²(4, N \= 100\) \= 4.44, p \= 0.349)

## Environmental Factors: 

Daily temperature trends across the different photoperiod treatments were illustrated using a line graph. Statistical analysis revealed that photoperiod did not significantly affect temperature (p \= 0.791), with the assumptions of normality and homogeneity of variance being met (Shapiro-Wilk test, p \= 0.60; Bartlett’s test, p \= 0.55). Repeated measure ANOVA revealed no significant differences in temperature among photoperiod groups (F(4,25) \= 0.42, p \= 0.79). These results suggest that the environmental conditions of temperature remained consistent across photoperiod treatments.

![][image7]

Figure 6: Temperature Across Days by Photoperiod (F(4,25) \= 0.42, p \= 0.79)

Similarly, humidity measurements over the course of the experiment were plotted by photoperiod treatment. No significant differences in humidity were detected among photoperiods (p=0.460), although the normality assumption for residuals was not fully satisfied (p=0.014). Repeated-measures ANOVA revealed no significant effect of photoperiod on humidity (F(4,25)=0.93, p=0.46), and the assumption of equal variances was met (p=0.75). These results suggest that moisture remained consistent across photoperiod treatments.

![][image8]

Figure 7: Humidity Across Days by Photoperiod (F(4,25)=0.93, p \= 0.46)

# Discussion: 

The statistical results of this study revealed that photoperiod did not significantly impact the core behavioral outcomes of dispersal, burial, or perching in Haliplus punctatus under controlled laboratory conditions. Chi-square tests indicated no significant associations between photoperiod treatments and dispersal rates (p \= 0.439, V \= 0.194), burial behavior (p \= 0.239, V \= 0.235), or perching behaviors either in water (p \= 0.839, V \= 0.120) or out of water (p \= 0.349, V \= 0.211). These findings suggest that variation in light exposure alone did not drive substantial differences in these behaviors within the parameters and time frame of this experiment. This aligns with previous research, which emphasizes that photoperiodic responses in insects can be complex and often involve integration with other environmental cues, such as temperature and humidity.

However, survival analysis of dispersal events, in contrast to the single-time-point results, highlighted a significant overall effect of photoperiod on dispersal timing (Cox proportional hazards: p \= 0.0019; likelihood ratio test: X² \= 17.05, df \= 4, N \= 1200). Specifically, beetles exposed to constant light (24-hour photoperiod) dispersed at a significantly lower rate compared to those in the 12-hour reference group (hazard ratio \= 0.73, p \= 0.029). In contrast, the 8-hour group showed a trend toward higher dispersal that did not reach statistical significance. Environmental factors were thoroughly monitored, with one-way ANOVAs confirming no significant differences in temperature (p \= 0.791) or humidity (p \= 0.460) across photoperiod treatments. 

The hypothesis and expectations set by previous field-based research cited in the introduction (e.g., Csabai et al., 2006; Boda & Csabai, 2009), the chi-square analyses revealed no significant association between photoperiod treatments and most behavioral outcomes—dispersal rates, burial, and perching frequencies showed no substantial differences across light regimes. This suggests that, when other environmental variables like temperature and humidity are held constant, variation in day length alone may not be a strong direct driver of these behaviors in Haliplus punctatus. This finding challenges the idea introduced that photoperiod is a primary regulator of these behaviors and is consistent with the noted gap in mechanistic understanding due to confounding environmental factors in prior field studies.

## Interestingly, the survival analysis revealed that beetles under constant light (24-hour photoperiod) dispersed at a significantly lower rate than those in the 12-hour reference photoperiod. This nuanced suppression of dispersal under continuous light supports the introduction's concept that photoperiod and circadian rhythms influence behavior, but it also highlights the complexity of such regulation. The diminished dispersal under uninterrupted light may reflect disruption to endogenous circadian clocks, as analogous effects have been observed in other insect species (Cajochen et al., 2004; Krishnan & Lyons, 2015). This finding reinforces the introduction’s emphasis on the circadian modulation of physiological and behavioral processes and the potential for artificial light pollution to disrupt natural rhythms.

If we step back from the main finding and place it in a broader experimental context, the comparison with laboratory results reveals further nuances. In the current study, burial behavior showed no significant variation across photoperiod treatments after three days, suggesting that light duration alone does not trigger short-term burial responses. Dispersal was suppressed only under continuous 24-hour light, whereas natural day–night cycles and exceptionally short 8-hour photoperiods tended to sustain or even increase movement. In contrast, Boersma et al. (2019) reported that temperature emerged as the pivotal driver in a factorial design that manipulated temperature, water level, and conductivity: as temperature rose, burial decreased while dispersal increased, with water level and conductivity exerting no detectable effects. Collectively, these findings indicate that temperature—not photoperiod—is the primary cue for burial behavior in these aquatic beetles. This distinction illustrates how different environmental factors selectively regulate distinct behaviors and emphasizes the multifaceted nature of behavioral responses under climate change.

## The lack of significant behavioral changes in burial and perching suggests either that these behaviors are less sensitive to photoperiod alone or that the experimental duration, sample size, or laboratory conditions limited the detection of subtler effects. The introduction posited that multiple environmental cues—such as temperature, humidity, and predator presence—likely interact with photoperiodic signals to influence dispersal and other behaviors in nature (Guppy, 1982; Iversen et al., 2017). The present study’s controlled environment, which effectively ruled out temperature and humidity variation as confounders, may have inadvertently isolated photoperiod effects to a degree not experienced in natural habitats, thus diminishing behavioral responses reliant on complex cue integration.

## This study partially confirms the introduction’s suggestion that photoperiod can influence aquatic beetle behavior, notably through circadian regulation, as evidenced by responses to continuous light exposure. However, the generally limited effects observed warn against assuming photoperiod is a sole or dominant cue for the studied behaviors. Future research should adopt more ecologically realistic designs, incorporating additional environmental variables and longer experimental durations, to clarify the interplay between photoperiod and other factors in shaping beetle behavior. Such work would advance understanding of how environmental rhythms coordinate key ecological behaviors, a critical step given the increasing prevalence of artificial light pollution affecting insect populations.

Future research should expand on these findings by incorporating additional environmental variables, such as temperature shifts, humidity gradients, or predation risk, alongside photoperiod manipulation. This approach may more accurately replicate natural environments and elicit stronger behavioral responses. It would also be valuable to test longer durations, different species, and to validate laboratory results in a field-based setting. Ultimately, refining behavioral measurement techniques and increasing sample sizes could enhance sensitivity to subtle effects, thereby advancing our understanding of how environmental rhythms coordinate basic survival and dispersal strategies in aquatic beetles.

## Acknowledgments:

The author gratefully acknowledges Dr. Kate Boresma for her invaluable guidance, expertise, and mentorship throughout this research project. Her insights and encouragement were instrumental in the development and execution of this study. I also extend my sincere appreciation to Taylor Romano, Mia Cook, Lauren Kirkland, and Chiedochie Madu for their essential contributions to data collection, specimen maintenance, and fieldwork. Their dedicated assistance with beetle husbandry and fieldwork protocols was crucial to the successful completion of this research. Thanks are also extended to Shem and the Biology Department for their support and the use of USD materials, to Jeremy Monroe and Corte Madera Pond, and to friends and family for their support throughout this experiment.

# References:

Boda, P., & Csabai, Z. (2009). Seasonal and diel flight activity patterns of aquatic Coleoptera and Heteroptera. Acta Biologica Debrecina, [https\://doi.org/10.1080/03680770.2009.11923928](https://doi.org/10.1080/03680770.2009.11923928).

Boda, P., & Csabai, Z. (2013). When do beetles and bugs fly? A unified scheme for describing seasonal flight behaviour of highly dispersing primary aquatic insects. Hydrobiologia, 703(1), 133-144. [https\://doi.org/10.1007/S10750-012-1350-3](https://doi.org/10.1007/S10750-012-1350-3).

Boda, P., Horváth, G., Kriska, G., Blahó, M., & Csabai, Z. (2014). Phototaxis and polarotaxis hand in hand: Night dispersal flight of aquatic insects distracted synergistically by light intensity and reflection polarization. Naturwissenschaften, 101(5), 385-395. [https\://doi.org/10.1007/S00114-014-1166-2](https://doi.org/10.1007/S00114-014-1166-2).

Bernáth, B., Gál, J., & Horváth, G. (2004). Why is it worth flying at dusk for aquatic insects? Polarotactic water detection is easiest at low solar elevations. Journal of Experimental Biology, 207(5), 755-765. [https\://doi.org/10.1242/JEB.00810](https://doi.org/10.1242/JEB.00810).

Cajochen, C., Knoblauch, V., Wirz-Justice, A., Kräuchi, K., Graw, P., & Wallach, D. (2004). Circadian modulation of sequence learning under high and low sleep pressure conditions. Behavioural Brain Research, 151(1-2), 167-176. [https\://doi.org/10.1016/J.BBR.2003.08.013](https://doi.org/10.1016/J.BBR.2003.08.013).

Csabai, Z., Boda, P., Bernáth, B., Kriska, G., & Horváth, G. (2006). A ‘polarisation sun-dial’ dictates the optimal time of day for dispersal by flying aquatic insects. Freshwater Biology, 51(7), 1361-1370. [https\://doi.org/10.1111/J.1365-2427.2006.01576.X](https://doi.org/10.1111/J.1365-2427.2006.01576.X).

Csabai, Z., Kálmán, Z., Szivák, I., & Boda, P. (2012). Diel flight behaviour and dispersal patterns of aquatic Coleoptera and Heteroptera species with special emphasis on the importance of seasons. Naturwissenschaften, 99(8), 661-674. [https\://doi.org/10.1007/S00114-012-0957-6](https://doi.org/10.1007/S00114-012-0957-6).

Genung, W. G. (1972). Seasonal occurrence of click beetles (Coleoptera: Elateridae) in the Everglades as measured by two types of traps. Florida Entomologist, 55(1), 43-51. [https\://doi.org/10.2307/3493640](https://doi.org/10.2307/3493640).

Guppy, J. C. (1982). Effects of temperature and light intensity on nocturnal activity patterns of the northern June beetle, Phyllophaga fusca, and the common June beetle, P. anxia (Coleoptera: Scarabaeidae). The Canadian Entomologist, 114(12), 1151-1158. [https\://doi.org/10.4039/ENT1141151-12](https://doi.org/10.4039/ENT1141151-12).

Horváth, G. (2014). Polarization patterns of freshwater bodies with biological implications. In Polarized Light and Polarization Vision in Animal Sciences (pp. 365-386). Springer. [https\://doi.org/10.1007/978-3-642-54718-8\_16](https://doi.org/10.1007/978-3-642-54718-8_16).

Horváth, G., & Csabai, Z. (2014). Polarization vision of aquatic insects. In Polarized Light and Polarization Vision in Animal Sciences (pp. 117-135). Springer. [https\://doi.org/10.1007/978-3-642-54718-8\_5](https://doi.org/10.1007/978-3-642-54718-8_5).

Horváth, G., Kriska, G., & Robertson, B. A. (2014). Anthropogenic polarization and polarized light pollution inducing polarized ecological traps. In Polarized Light and Polarization Vision in Animal Sciences (pp. 449-475). Springer. [https\://doi.org/10.1007/978-3-642-54718-8\_20](https://doi.org/10.1007/978-3-642-54718-8_20).

Iversen, L., Rannap, R., Briggs, L., & Sand‐Jensen, K. (2017). Time-restricted flight ability influences dispersal and colonization rates in a group of freshwater beetles. Ecology and Evolution, 7(7), 2234-2244. [https\://doi.org/10.1002/ECE3.2680](https://doi.org/10.1002/ECE3.2680).

Jarillo, J. A., del Olmo, I., Gómez-Zambrano, Á., Lázaro, A., López-González, L., Miguel, E., Narro-Diego, L., Sáez, D., & Piñeiro, M. (2008). Photoperiodic control of flowering time. Plant Signaling & Behavior, 3(5), 337-340.

Krishnan, H. C., & Lyons, L. C. (2015). Synchrony and desynchrony in circadian clocks: Impacts on learning and memory. Learning & Memory, 22(9), 426-437. [https\://doi.org/10.1101/LM.038877.115](https://doi.org/10.1101/LM.038877.115).

Landin, J. (1976). Seasonal patterns in abundance of water-beetles belonging to the Hydrophiloidea (Coleoptera). Freshwater Biology, 6(1), 55-69. [https\://doi.org/10.1111/J.1365-2427.1976.TB01594.X](https://doi.org/10.1111/J.1365-2427.1976.TB01594.X).

Lyons, L. C., & Roman, G. (2009). Drosophila circadian modulation of short-term memory. Communicative & Integrative Biology, 2(5), 419-420.

Micallef, B. J. (2011). Circadian clocks/photoperiodism and crop quality. In Comprehensive Biotechnology (2nd ed.). Elsevier. [https\://doi.org/10.1016/B978-0-08-088504-9.00242-7](https://doi.org/10.1016/B978-0-08-088504-9.00242-7).

Miguélez, D., & Valladares, L. F. (2008). Seasonal dispersal of water beetles (Coleoptera) in an agricultural landscape: A study using Moericke traps in Northwest Spain. Annales de la Société Entomologique de France, 44(2), 183-190. [https\://doi.org/10.1080/00379271.2008.10697570](https://doi.org/10.1080/00379271.2008.10697570).

Nag, N., Sasidharan, S., Saudagar, P., & Tripathi, T. (2023). Fundamentals of spectroscopy for biomolecular structure and dynamics. Elsevier. [https\://doi.org/10.1016/B978-0-323-99127-8.00002-7](https://doi.org/10.1016/B978-0-323-99127-8.00002-7).

Page, T. (2009). Circadian regulation of olfaction and olfactory learning in the cockroach Leucophaea maderae. Physiological Entomology, 34(2), 169-177. [https\://doi.org/10.1111/J.1479-8425.2009.00409.X](https://doi.org/10.1111/J.1479-8425.2009.00409.X).

Page, T. L. (2001). Circadian systems of invertebrates. In Handbook of Behavioral Neurobiology (Vol. 12, pp. 65-96). Springer. [https\://doi.org/10.1007/978-1-4615-1201-1\_5](https://doi.org/10.1007/978-1-4615-1201-1_5).

Schwind, R. (1991). Polarization vision in water insects and insects living on a moist substrate. Journal of Comparative Physiology A, 169(5), 531-540. [https\://doi.org/10.1007/BF00193544](https://doi.org/10.1007/BF00193544).

Tanaka, S., Denlinger, D. L., & Wolda, H. (1988). Seasonal changes in the photoperiodic response regulating diapause in a tropical beetle, Stenotarsus rotundus. Journal of Insect Physiology, 34(5), 409-414. [https\://doi.org/10.1016/0022-1910(88)90216-8](https://doi.org/10.1016/0022-1910\(88\)90216-8).

Vebrová, L., van Nieuwenhuijzen, A., Kolář, V., & Boukal, D. S. (2018). Seasonality and weather conditions jointly drive flight activity patterns of aquatic and terrestrial chironomids. BMC Ecology, 18(1), 1-13. [https\://doi.org/10.1186/S12898-018-0175-Y](https://doi.org/10.1186/S12898-018-0175-Y).


