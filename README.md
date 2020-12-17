# projectCOVID-19
University group project for modeling Covid-19 at Chalmers University of Technology

## INITIAL INSTRUCTIONS FROM TEACHERS:

The  Coronavirus  pandemic  was  the  biggest  event  globally  this  year.  Many  people  got  sick  with  minor symptoms,  some  ended  up  in  the  intensive  care  units  (ICUs),  and some  portion  of  those  infected  died. It  affected  every  aspect  of  everyone’s  life:  national borders  closed,  flights  were  suspended,  schools  closed, working  from  home  was instituted,  social  distancing  measures  were  put  in  place,  in  some  countries  face masks were  required,  and  washing  your  hands  often  became  a  necessity.  _Why  did  the government  adopt these measures? Did we do these things to protect ourselves? Or to protect the others? Why? How?_

Recall all the information you received during the outbreak: news clips, infographic you saw in the newspapers, pictures,  etc. _Draw  a Concept  Map of  how  Coronavirus  spread,  and  what  are  believed  to  be  effective preventive measures?_

Among the information you received, try to _identify one or few simple mathematical model(s)
that were used to predict the outbreak and the effectiveness of the interventions. Try to explain those models. What do  you think  were  used  to make  the  predictions?  What were the  input variables?  What  were the  output variables? What was the relationship or the equations in those models? Do you think they were good models (How do you determine if a model is “good”)? What do you think they missed? What do you think can be improved? Which information do you think was missing? Compare  your  concept  map  with  the  observations  you  made  in  Walk  and  talk  II:  The  places  COVID-19 touched.  Were  your  observations  consistent  with  the  “best”  advice  you  would  have  given  if  you  were the expert after studying these models?_

#### In a group of 4, make a pecha-kucha presentation (a slideshow with 20 slides where each slide stays for exactly 20 second) that includes at least the following:

 - A Concept Map of how coronavirus spread and possible interventions;

 - Present a mathematical model(s) that can make a prediction of the outbreak and a critique of the model(s) 

 - Compare the knowledge you learn from the model and the experience you had in Walk and talk II: The places COVID-19 touched, point out the gaps and
 inconsistencies and reflect on why the gaps exist and what can be done about them?

 - Upload  your  model  to Github  or  any  website that  supports Open  Model/Open  Code/Open source. Make sure that the model is easy to assess and fullydocumented. Download a model developed by the other team from this class. Run their model and compare with your results.


## RESOURCES:

Simple SIR model Let’s start with the basics. The SIR model is the most basic model to capture the spread of disease. You can find excellent resources here to help you get started with the basic: the differential equation model. Or, if you are still not comfortable with programming with differential equations, then you can use Euler’s Method for Systems, which you can program in Excel.

You can find examples of the simple SIR model code in R, such as https://www.r-bloggers.com/sir-model-with-desolve-ggplot2/, which publishes the code in GitHub https://github.com/eugejoh/SIR-interact . Or, you can find sample codes in this course in C++ Program,  Python  Program, Fortran Program, Parameters, MATLAB  Code. There  are tons of  resources out there. Take advantage of Google and find useful resources that suit you the best. SIR model with mortality Numerous infectious diseases, such as malaria, measles, whooping cough, SARS, and the most relevant one here, COVID-19, are  associated with a substantial mortality  risk.  How  do  we explore the consequences of infection-induced mortality? Specifically, how do we  incorporate a mortality probability into the SIR equations? Here is a good resource: http://homepages.warwick.ac.uk/~masfz/ModelingInfectiousDiseases/Chapter2/Program_2.4/index.html (but you can go ahead and ignore the birth rate and the death, assuming them as zero given that we are working on a static model (few months to  a  year). The obvious approach  would  be to add a term  -1/(1-) I to the basic equation, where is the probability of an individual in the I class dying from the infection before recovering.)

#### COVID-19 resources:

 - A great resource about Information and Resources for COVID-19 Modeling Research: https://midasnetwork.us/covid-19/. 

 - COVID-19 scientific resources by Imperial College London: 
 https://www.imperial.ac.uk/mrc-global-infectious-disease-analysis/covid-19/covid-19-scientific-resources/ 

 - Assorted Links on COVID19: https://urbandemographics.blogspot.com/2020/04/assorted-links-on-covid19.html. 

 - Special report: The simulations driving the world’s response to COVID-19 How epidemiologists rushed to model the coronavirus pandemic.
 https://www.nature.com/articles/d41586-020-01003-6 
