[![GitHub issues](https://img.shields.io/github/issues/arjunparmar/COVID-19?style=for-the-badge)](https://github.com/arjunparmar/COVID-19/issues) [![GitHub forks](https://img.shields.io/github/forks/arjunparmar/COVID-19?style=for-the-badge)](https://github.com/arjunparmar/COVID-19/network) [![GitHub stars](https://img.shields.io/github/stars/arjunparmar/COVID-19?style=for-the-badge)](https://github.com/arjunparmar/COVID-19/stargazers) [![GitHub license](https://img.shields.io/github/license/arjunparmar/COVID-19?style=for-the-badge)](https://github.com/arjunparmar/COVID-19/blob/master/LICENSE.md)
# COVID-19
COVID-19 (coronavirus disease 2019) is an infectious disease caused by **severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2)**, previously known as 2019 novel coronavirus (2019-nCoV), a strain of coronavirus. The first cases were seen in Wuhan, China, in late December 2019 before spreading globally. The current outbreak was officially recognized as a pandemic on **11 March 2020**.No effective treatment or vaccine exists currently (April 2020).
# DESCRIPTION
Since reverse transcription polymerase chain reaction (RT-PCR) test kits are in limited supply, there exists a need to explore alternative means of identifying and prioritizing suspected cases of COVID-19. In our City of Gujarat, Surat, turnaround time for COVID-19 test results is currently reported as 24 hours. It is possible that this turnaround time is even greater in rural and remote regions.
Moreover, large scale implementation of the COVID-19 tests which are extremely expensive cannot be afforded by many of the developing & underdeveloped countries hence if we can have some parallel diagnosis/testing procedures using Artificial Intelligence & Machine Learning and leveraging the historical data, it will be extremely helpful. This can also help in the process to select the ones to be tested primarily.
## Why Study X-Rays?
CT scans, despite being used to contribute to the clinical workup of patients suspected for COVID-19, are costly. Therefore, smaller centres may have limited access to CT scanners. X-ray machines are more affordable and can be portable and therefore a viable alternative.
To be clear, We don't claim that CXRs should be relied on in the diagnosis of COVID-19. Direction from the Canadian Association of Radiologists recommend following the CDC’s guidelines that state that CXR and CT should not be used to diagnose COVID-19. The recommendations state that viral testing is currently the only means to diagnose COVID-19, even if a patient has suggestive features on CXR or CT. That being said, some research has suggested that radiological imaging (CT in particular) may be just as sensitive as RT-PCR. Such findings exhibit why we’ve decided to explore this avenue and build open source tools to enable further investigation. It is also important to note that normal imaging does not imply that a patient has not been infected by SARS-CoV-2, only that they aren’t showing signs of COVID-19 respiratory disease.
## Goal
Determine if a machine learning classifier can be trained to distinguish cases of COVID-19 from CXRs.
# DATA
## DATASET
For the purpose of this experiment, data was taken from two repositories:<br/>
1)The [COVID-19 image data collection](https://github.com/ieee8023/covid-chestxray-dataset) repository on GitHub is a growing collection of deidentified CXRs and CT scans from COVID-19 cases internationally. We would like to take this opportunity to thank Joseph Paul Cohen and his fellow collaborators at the University of Montreal for their hard work in assembling this dataset. See Figure 1a for an sample image.<br/>
2)The [Chest X-Ray Images (Pneumonia) dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) available on Kaggle contains several deidentified CXRs and includes a label indicating whether the image shows evidence of pneumonia. We would like to take this opportunity to thank the Paul Mooney Developer Advocate at KaggleBoulder, United States and all other involved entities for creating this dataset. See Figure 1b for an sample image.<br/>
|![](https://github.com/arjunparmar/COVID-19/blob/master/Data/Images/Positive.jpg)|![](https://github.com/arjunparmar/COVID-19/blob/master/Data/Images/Negative.jpg)|
|:---: | :---: |
|Figure 1a|Figurw 1b|
