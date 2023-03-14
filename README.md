# **Seal Weight vs Days in Rehabilitation: An Indication of Health?**
## MACS 401 Final Project 
Rachel Meade\
Winter 2023

## Research Question
Is there a correlation between a harbor seal's weight and the number of days spent in rehabilitation, which can be used to predict its survivability in a marine mammal rehabilitation setting?

## Goal
-To analyze the gathered data to see if there is a correlation between a harbor seal's weight and the number of days spent in rehabilitation in relationship to survivability or being released.\ 
-To create a program from the analyzed data that a rehabilitaor will be prompted to input "Intake Date", "Current Weight(g)", and "Todays Date". The output of these three values will put a new point (red) on the plot for Ordinal Day vs Daily Change so the rehabilitaor can see where their inputted seal lies compared to previous seals in rehabilition for the same ordinal day and weight in rehabilitaion. 


To create a program in which a marine mammal rehabilitator can input a seals intake weight, current weight, and number of days in rehabilitation to see if the pinniped is consistent with a healthy weight trajectory compared to previous seals. Additionally, present data of deceased seals to raise concern if the seal is following the weight trajectory of seals that ended up dying. 

## Motivation
Over this last summer I was an intern at Sea Life Response, Rehabilitation, and Research (SR3). During my time there we had a seal, Azha, who would not willingly eat nor was gaining weight. We assumed she was just having a hard time adjusting, which is common for seals in rehababilitaion. It turned out she had megaesophagus and a hiatal hernia which meant she could not properly transport food from the esophagus to the stomach and through the rest of the digestive system. Therefore Azha could not keep food in her stomach or food that was digested would not make it through the large intestine. This was likely caused by her hernia which created. thin lining in her diaphragm causing the stomach to slide up against and in and out of the diaphragm. If there had been a way to see her drastic weight difference compared to seals that had been released (or similarity the weight of seals who had died) there may have been more alarm to further evaluate her condition and possibly find solutions or humanely euthanize her sooner. With this program, there will be less of a question of "Is this normal?" or "Is this cause for concern?" as there will be an established data set for what is "normal" weight gain for a seal in rehabilitation on the path for being healthy and released vs a seal who is not progressing and will likely not recover. 


## Data
My data comes directly from SR3. It includes the weights of 32 seals (23 of which were released, 9 which died in hospital) from May 2022 - February 2023 for a total of 517 data points. Each data point includes seal ID, date, weight (g), and intake date. 

## Analysis Methods
I have organized my data into a fashion that will easily be understood by Python. The data has been transferred to a .csv and uploaded to Python. Next I will, seperate the deceased (T/F) into linear regression patterns to see if there is a difference in weight gain between seals that were released(F) or deceased(T). From this pattern I will create a program that takes
*Intake Weight*, *Intake Date*, and *Current Date* and will plot where the seal's current weight lies relative to past seals. If the seal is close to the regression line for released(F) seals then the rehabilitator knows the seal is likely on track to be released. However, if the seals weight is far below the released(F) regression line and is closer to the deceased(T) regression line, this will bring awarness to the seal's weight and indicate a possible underlying issue. 

