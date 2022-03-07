### Introduction

The project code can be found [here](https://github.com/chinkevin/DSC180_sleep_apnea).

In this project, we aim to explore sleep stage classification for individuals specifically with [sleep apnea](https://www.mayoclinic.org/diseases-conditions/sleep-apnea/symptoms-causes/syc-20377631). Current sleep stage scoring is done by hand which is somewhat subjective so human scorers don’t agree a lot of the time. Moreover, current automated sleep stage scoring models don't generalize well to patients with sleep apnea. 

This work is important because sleep apnea can cause serious health issues for patients. It increases the risk of stroke, breathing problems, obesity, heart failure, and even sudden death. So the analysis of sleep data is essential for understanding and diagnosing sleep-related diseases in order to prevent life-changing health problems.

Our goal is to further explore the relationship between sleep stages and sleep apnea by building a sleep stage classifier that specifically includes ECG signals. We suspect that including ECG signals will improve the current models’ performance because it can identify obstructive sleep events, such as waking during sleep cycle, which individuals with sleep apnea often encounter.



### Our Data

The data we have chosen to work with comes from the National Sleep Research Resource (NSRR). Specifically, we used the Sleep Heart Health Study (SHHS) which consists of two visits and the respective overnight [polysomnography](https://www.mayoclinic.org/tests-procedures/polysomnography/about/pac-20394877#:~:text=Polysomnography%2C%20also%20called%20a%20sleep,leg%20movements%20during%20the%20study.) recordings. Since the second visit has less participants and was done more recently, to make sure we had a more reliable and complete dataset we continued with the second visit (SHHS 2). This visit consists of 2,651 subjects and their respective 9 hour recordings of EEG, EOG, EMG, and ECG signals in 30 second periods. 

To learn more about the full dataset, check out this [link] (https://sleepdata.org/datasets/shhs/pages/04-dataset-introduction.md)

Here is a snippet of a single participant’s signal recordings:
![visit2](images/visit2.png)

### Our Methods

### Models and Performance

### Result

### Reference

Vallat, Raphael, and Matthew P. Walker. “A Universal, Open-Source, High-Performance Tool for Automated Sleep Staging.” BioRxiv, Cold Spring Harbor Laboratory, 1 Jan. 2021, https://www.biorxiv.org/content/10.1101/2021.05.28.446165v1.full.

https://www.mayoclinic.org/diseases-conditions/sleep-apnea/symptoms-causes/syc-20377631


### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/YilanG08/YilanG08.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
