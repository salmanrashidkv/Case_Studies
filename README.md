# Case_Studies
This repository hosts sample projects that demonstrate various real-world scenarios using different datasets.

### 1. Parkinsons Disease Detection Using Ensemble Methods
The data consists of those diagnosed with Parkinson's Disease and those who do not.

#### Source:

The dataset was created by Max Little of the University of Oxford, in collaboration with the National Centre for Voice and Speech, Denver, Colorado, which recorded the speech signals. The original study published the feature extraction methods for general voice disorders.

##### Data Set Information:

This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds to one of 195 voice recordings from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to the "status" column which is set to 0 for healthy and 1 for PD.

#### Attribute Information:

name - _ASCII subject name and recording number_
MDVP:Fo(Hz) - _Average vocal fundamental frequency_
MDVP:Fhi(Hz) - _Maximum vocal fundamental frequency_
MDVP:Flo(Hz) - _Minimum vocal fundamental frequency_
MDVP: Jitter(%), MDVP: Jitter(Abs), MDVP: RAP, MDVP: PPQ, Jitter: DDP - _Several measures of variation in fundamental frequency_
MDVP:Shimmer, MDVP: Shimmer(dB), Shimmer: APQ3, Shimmer: APQ5, MDVP: APQ, Shimmer: DDA - _Several measures of variation in amplitude_
NHR, HNR - _Two measures of the ratio of noise to tonal components in the voice_
RPDE, D2 - _Two nonlinear dynamical complexity measures_
DFA - _Signal fractal scaling exponent_
spread1, spread2, PPE - _Three nonlinear measures of fundamental frequency variation_
Status - _Health status of the subject (one) - Parkinson's, (zero) - healthy_
