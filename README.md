# OceanDataAnalytics-OpenPsychometrics

Visualization of Data Obtained from test hosted on OpenPsychometrics.org. Data was obtained from the following link https://www.kaggle.com/datasets/lucasgreenwell/ocean-five-factor-personality-test-responses. The data was a .csv file originally containing 19,720 entries. It contained about 50 questions which were divided into 10 questions per trait. Each question was answered from 1 to 5. It also contained information about the respondant's age, gender, ethnicity, nationality and their preferred hand usage.
[codebook.txt](https://github.com/hamzaashfaque/OceanDataAnalytics-OpenPsychometrics/files/11539774/codebook.txt)

After obtaining the data, it was transformed using pandas and numpy library in Python. The 5 trais were calculated from the answers to the original questions. Anomolies in data were removed. The data was properly formatted by converting some birthdays in the age section to the age in years and converting unspecified data to NaN values. The data was then exported as another .csv file. The data was then visualized using Microsoft's Power BI tool and a simple dashboard was made.
