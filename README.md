# ML Exceptional Drug Responders Project

This project was completed by Max Petruzzi and Guillaume Bonheure, two Master of Business Analytics candidates from MIT, for the course 15.095 - Machine Learning through a Modern Optimization Lens with Dr. Dimitris Bertsimas.

The goal was to identify patient subpopulations, based on a defined range of laboratory results and demographics, that respond exceptionally well to a particular treatment for Primary Billiary Cirrhosis. When evaluating whether a particular drug is right for a patient, physicians weigh the expected treatment effect of the drug versus the potential risk. Patients within the subpopulations we found have an exceptionally high treatment effect, which may make them better candidates for this treatment versus alternatives.

Our approach to find the criteria for defining these subpopulations was an extension of the methodology proposed in the following paper:  
Bertsimas, D., Korolko, N., & Weinstein, A.M. (2019). Identifying Exceptional Responders in Randomized Trials: An Optimization Approach. INFORMS Journal on Optimization.

For more information on our methods and findings, please see the article found in the repo entitled ARTICLE.pdf or the slide deck entitled SLIDES.pdf. Thanks!

______________________________________________________________________________________________________________________________

### Datasets:

The main data set was from a 1991 Mayo Clinic clinical trial for the drug D-Penicillamine for the indication Primary Billiary Cirrhosis:  
Fleming TR & Harrington DP (1991): Counting Processes & Survival Analysis. New York: Wiley; Appendix D; courtesy Dr Terry Therneau of Mayo Clinic

Accessed from:  
https://hbiostat.org/data/

The supplementary data set we used was from a 1994 Mayo Clinical clinical trial for a different drug, Ursodeoxycholic acid, for the same indication:  
Lindor KD, Dickson ER, Baldus WP, Jorgensen RA, Ludwig J, Murtaugh PA, Harrison JM, Wiesner RH, Anderson ML, Lange SM, et al. Ursodeoxycholic acid in the treatment of primary biliary cirrhosis. Gastroenterology. 1994 May;106(5):1284-90. doi: 10.1016/0016-5085(94)90021-3. PMID: 8174890.

This was accessed from:  
https://rdrr.io/cran/survival/man/udca.html



