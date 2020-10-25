# MPED
MPED: A Multi-Modal Physiological Emotion Database for Discrete Emotion

Abstract  
To explore human emotions, we design and build a multi-modal physiological emotion database, which collects four modal physiological signals, i.e., electroencephalogram (EEG), galvanic skin response, respiration, and electrocardiogram (ECG). To alleviate the influence of culture dependent elicitation materials and evoke desired human emotions, we specifically collect an emotion elicitation material database selected from more than 1500 video clips. By the considerable amount of strict man-made labeling, we elaborately choose 28 videos as standardized elicitation samples, which are assessed by psychological methods. The physiological signals of participants were synchronously recorded when they watched these standardized video clips that described six discrete emotions and neutral emotion.  
![image](https://github.com/Tengfei000/MPED/blob/datatset/MPED.jpg)  
Details of the presented standardised Chinese emotion elicitation material database:  
![image](https://github.com/Tengfei000/MPED/blob/datatset/elicitaition_material.jpg)  
Database files:  
raw_EEG_signals : The raw EEG signals.  
EEG_feature : HHS, Hjorth, HOC, PSD and STFT features.  
GSR_RSP_ECG_raw_signals : The raw GSR, RSP and ECG signals.  
GSR_RSP_ECG_features :   
ECG: 8 mean energy values, 8 subband spectral entropy values, mean and the standard deviation of Normal-to-normal (NN) interval.  
GSR: mean value, standard deviation, and the mean of first and second derivations.  
RSP:  2energy mean values and 2 SSE values, mean value and the standard deviation of all peak-to-peak (PP) intervals.  
label : 0-resting status, 1-neutral, 2-joy, 3-funny, 4-angry, 5-fear, 6-disgust, 7-sadness  

Note:  
Training trials: [2,3,4,5,6,7,8,9,10,11,12,13,14,15,17,18,19,20,23,25,27]  
Testing trials: [21,22,24,26,28,29,30]  

**If you want to apply for this database, please download the license and follow the introduction.**  

Reference:  
[1] Song T, Zheng W, Lu C, et al. MPED: A Multi-Modal Physiological Emotion Database for Discrete Emotion Recognition[J]. IEEE Access, 2019, 7: 12177-12191.
BibTeX:
@article{song2019mped,  
  title={MPED: A multi-modal physiological emotion database for discrete emotion recognition},  
  author={Song, Tengfei and Zheng, Wenming and Lu, Cheng and Zong, Yuan and Zhang, Xilei and Cui, Zhen},  
  journal={IEEE Access},  
  volume={7},  
  pages={12177--12191},  
  year={2019},  
  publisher={IEEE}
}
