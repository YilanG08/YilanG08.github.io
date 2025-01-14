### Introduction

The project code can be found [here](https://github.com/chinkevin/DSC180_sleep_apnea).

Obstructive sleep apnea (OSA), the more common form of sleep apnea, is a sleeping disorder where breathing stops and starts intermittently. OSA happens when muscles in the throat get relaxed, narrowing the airway and hampering breathing for 10 seconds or longer, causing blood oxygen concentration to decrease and a buildup of carbon dioxide. Such sudden drops in oxygen levels cause sudden increases in heart rate and blood pressure, resulting in repeated, transient strains on the cardiovascular system. OSA increases the risk of stroke and the risk of irregular heart rhythms or arrhythmias; both stroke and arrhythmias have the potential to cause sudden death. 

Sleeping is not uniform and consists of four stages: N1, N2, N3, and REM sleep. The analysis of sleep stages is essential for understanding and diagnosing sleep-related diseases, such as insomnia, narcolepsy, and sleep apnea.; however, there is not enough research on sleep stages and sleep stage classification for sleep apnea. The goal of our project is to identify and classify the sleep stage for people with sleep apnea and understand how it differs from the normal sleep stage.

This report aims to document scientific investigations we have done on EEG classification and exploratory data analysis (EDA) performed on sleep polysomnography data provided by the Sleep Heart Health Study PSG Database under the National Heart Lung & Blood Institute. The methods we have examined and plan to build our model on are YASA classifier and LGBM classifier models. The result section contains the EDA of some essential exploration of the dataset to understand its characteristics and patterns, cleaning the missing values and irregularities such as outliers to improve our results, visualizations representing the data, and some analysis.


### Data

Because the SHHS consists of two visits, and the number of participants in the second visit is clearly smaller than that in the first visit, to make sure we have a complete record of both visit polysomnography data, we decided to start EDA on the second visit participants. 

All participants data in visit 2 are saved in this dataframe:
![visit2](https://github.com/YilanG08/sleepstage/blob/main/images/visit2.png)

![numeric](https://github.com/YilanG08/sleepstage/blob/main/images/numeric.png)

To accord with the epoch period in our later model planning, EEG, ECG, and EOG data are analyzed and visualized in 30-sec periods (One period EDA is shown in the Result section). We also plot an overnight spectrogram of EEG, which demonstrates the relationship between time and Frequency.



### Exploratory Data Analysis

### Feature Extraction

### Models and Performance

### Result

### Reference

Vallat, Raphael, and Matthew P. Walker. “A Universal, Open-Source, High-Performance Tool for Automated Sleep Staging.” BioRxiv, Cold Spring Harbor Laboratory, 1 Jan. 2021, https://www.biorxiv.org/content/10.1101/2021.05.28.446165v1.full.


### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/YilanG08/YilanG08.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
