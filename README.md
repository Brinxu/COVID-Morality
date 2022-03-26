# Sentiment Analysis on COVID-19 Postings

## Project Overview 

In this project, we seek to the understanding of audience engagement associated with moral content and sentiment in COVID-19 related topics. It contributes to theories by investigating how moral dimensions are associated with the diffusion of social media contents on science topics, a previously less understand and yet increasingly important topic.  

## Dataset Description

This study sample was downloaded from major U.S. news media’s Facebook public page using an app called CrowdTangle. Following the previous study, we chose 4 categories of new media: liberal (11), neutral (6), conservative (5), and science channels (24), 46 outlets in total. The dataset can be downloaded from [here](https://drive.google.com/drive/folders/1arjfRysDY4nwcsgwTbKBCkYeLl7tq3SB?usp=sharing).

We extracted these downloaded media postings from 2020/1/1 to 2021/6/30, considering COVID-19 topics were the most predominant during this time. Next, following previous studies, we used keywords to identify COVID-related posts for further analysis. These keywords are: Covid19, Covid, Corona, Coronavirus, 2019ncov, Ncov, Pandemic, Lockdown, Quarantine, SARS-CoV-2, N95, Social distancing. After topic selection, we got our working sample including 84,385 pieces of news. After eliminating missing value, we got final analytical sample of 61,463.  

## Approach Used

The notebook in the repository contains the whole process of generating results from input. It basically includes 4 parts:  processing data, conducting sentiment analysis, producing moral foundation scores, and conducing multilevel regressions. 

To run the notebook successfully, one has to first install libraries that are being used in the notebook. And to install them, the following command will be used: pip install -r requirements.txt. Then open the jupyter notebook, click on kernel-> Run all the cells.

## Key Findings

This study investigated how moral foundational scores relate to audience engagement in major media outlets’ Facebook postings. Further we examined how the pattern varies by media type, namely, liberal, conservatives, neutrals, and science channels. We do not find evidence supporting liberals are more responsive to postings with higher care and fairness dimensional scores, nor significant differences in the other 2 moral dimensions. But we find evidence that conservatives are more responsive to postings with higher authority dimensional scores. 

In addition, neutral medias postings have more audience engagement in fairness, loyalty, authority, and sanctity contents. Science channels, by contrast, seems only responsive at authority dimensional contents. By exploring how moral values drive audience engagement across media type, we contribute to understanding the nature of audience engagement in social media contents.  

<img width="527" alt="Screen Shot 2021-11-02 at 7 42 27 PM" src="https://user-images.githubusercontent.com/41206996/139966685-63074b28-f26f-41b7-97b9-ba7289ac0854.png">

<img width="500" alt="Screen Shot 2021-11-02 at 7 44 01 PM" src="https://user-images.githubusercontent.com/41206996/139966777-7c9bdbe5-b45e-4da2-b5a9-ac8c6735923a.png">

## Conclusion

The significance of COVID-19 topics and their impact on public health is the underlined reason we chose this topic from science topics. The approaches used can be easily reproduced to understand audience engagement in certain topic and explore the nature of agreement/disagreement. 
