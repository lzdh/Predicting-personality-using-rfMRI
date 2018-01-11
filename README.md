# Predicting-personality-using-rfMRI


This project uses functional connectivity from resting-state fMRI to predict the Big Five personality factors. We applied the analysis to two independent sets of data. One comes from the Southwest University, China, consisted of 131 subjects. The other is the HCP (Human Connectome Project) 900 release consisting of 815 subjects. 

For the dataset of Southwest Unviversity, we applied the Power (Power et al., 2011) and AAL2 (Rolls et al., 2015) atlases for brain parcellation seperatally. For Power atlas, Extraversion and Openness to Experience turned to be the most predictable factors having correlation 0.318 (p=2.068e-04) and -0.391 (p=3.915e-06) respectively. For the AAL2 percellation, among all five-personality factors, two had networks that could make significant predictions. One was Extraversion (r=0.2543, p=0.0034), and Openness to Experience (r=-0.2660, p= 0.0021).

For the HCP data, the brain was parcellated using ICA into 200 regions. Agreeableness turns to have the best performance (r=~0.16). However, after de-confounding (we de-confounded age, gender, height, weights etc. in total of 11 confounds), none of the five factors seems significant.


## License
All content in this repository is openly licensed with a CC BY 4.0, which means you're free to use the materials and remix them so long as you **credit the source**.

If you were to use content from this repo in your own work, please attribute me with a sentence like: 
> The material is (partially) derived from Zhangdaihong Liu's project "[Predicting personality using rfMRI](https://github.com/lzdh/Predicting-personality-using-rfMRI)".
