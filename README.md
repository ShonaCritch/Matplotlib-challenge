# Matplotlib-challenge


Audience:
The following executive report summarises the high level results from the Pymaceutical's SCC_Mouse phase one study.  

Background:
The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the drug regimens in the search for an effective treatement of squamous cell carcinoma (SCC), the most serious of the commonly occurring non-melenoma skin cancers. 

Method:
The study included 249 mice identified with SCC tumor growth; all were chosen with the same starting tumor volume of 45mm.   
The mice were split randomly into 10 treatement arms, 9 drugs and 1 placebo. 
The study took place of the course of 45 days, with tumor development observed and measured every 5 days. 

Analysis:
Data was cleaned and analysed in Python.  Duplicate data was removed for all mice where duplicate measures were taken; 1 mouse data set removed, leaving 248 mice in the analysis.
Basic inferential statistics, Mean, Median, SD, Var and Std Error were performed on all treatment arms and the placebo.  

Capomulin and 3 of the top performing treatments (Ramicane, Infubinol and Ceftamin), were compared using quartile plots. Capomulin was then analysed to further determine level of efficacy by plotting the treatment trajectory for a randomly selected mouse and finally with a linear regression (Pearsons r) of mouse weight compared to average tumor volume for Caplomulin to determine realtionship between weight of mouse (measures once at the commencement of the study) to the mean tumor volumes measured. As all mice, despite varying weights, started with the same tumor volume measures on day 0, it was predicted that if Capomulin is effective, a relationship will become apparent between average tumor measurement and starting mouse weight.  That is that the best predicator of mouse tumor size will be seen to be the mouses weight if Capomulin is effective at slowing and reducing tumor growth.

Results:
Inferential Statistics for all drug treatment arms
![mouse_drug](Images/mouse_drug.png)

![sex_piegrph](Images/sex_piegrph.png)

![pivot](Images/pivot.html)

Comparison of Capomulin against 3 of the other best performing drugs (Ramicane, Infubinol and Ceftamin) 
![boxes](Images/boxes.png)

Randomly selected Capomulin treatement mouse, tumor volume trajectory over treatment days
![mouse_line](Images/mouse_line.png)

Linear Regression of Mouse Weight and Average Tumor Volume for Capomulin treatment arm
![weight_av_TumorVol](Images/weight_av_TumorVol.png)

Discussion:
Capomulin was found to reduce tumor volume growth as demonstrated by low measures of central tendancy and variance.  This is clearly demonstrated in the random mouse treatment trajectory plotted, with is clear trend downwards across the lenght of the study.  The linear regression demonstrated a stong relationship between mouse weight at the commencement of the study and average tumor volume within the Capomulin treated mice with a Pearsons r of 0.84 and r squared of 0.71. Ramicane was another front-runner drug, with comparable inferntial results to Capomulin, the remaining drugs however, did not demonstrate as high efficacy as Capomulin.  

Recommendation:
The results support a recommendation that Capomulin progress to the next phase of clinical trials and that Ramicane should also be considered for further trials as it demonstrated similar treatment efficacy.


