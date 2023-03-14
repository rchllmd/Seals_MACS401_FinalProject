# **Seal Weight vs Days in Rehabilitation: An Indication of Health?**
## MACS 401 Final Project 
Rachel Meade\
Winter 2023

## Research Question
Is there a correlation between a harbor seal's weight and the number of days spent in rehabilitation, which can be used to predict its survivability in a marine mammal rehabilitation setting?

## Goal
-To analyze the gathered data to see if there is a correlation between a harbor seal's weight and the number of days spent in rehabilitation in relationship to survivability or being released.

-To create a program from the analyzed data that a rehabilitator will be prompted to input "**Intake Date**", "**Current Weight(g)**", "**Today's Date**", and "**Current Weight**". The output of these three values will put a new point (red) on the plot for Ordinal Day vs Daily Change so the rehabilitator can see where their inputted seal lies compared to previous seals in rehabilition for the same ordinal day and weight in rehabilitaion. 


## Motivation
Over this last summer I was an intern at Sea Life Response, Rehabilitation, and Research (SR3). During my time there we had a seal, Azha, who would not willingly eat nor was gaining weight. We assumed she was just having a hard time adjusting, which is common for seals in rehababilitaion. It turned out she had megaesophagus and a hiatal hernia which meant she could not properly transport food from the esophagus to the stomach and through the rest of the digestive system. Therefore Azha could not keep food in her stomach or food that was digested would not make it through the large intestine. This was likely caused by her hernia which created. thin lining in her diaphragm causing the stomach to slide up against and in and out of the diaphragm. If there had been a way to see her drastic weight difference compared to seals that had been released (or similarity the weight of seals who had died) there may have been more alarm to further evaluate her condition and possibly find solutions or humanely euthanize her sooner. The goal of this this program, was that there will be less of a question of "Is this normal?" or "Is this cause for concern?" as there will be an established data set for what is "normal" weight gain for a seal in rehabilitation on the path for being healthy and released vs a seal who is not progressing and will likely not recover. However, as found through data analyisis weight and ordinal day alone are not the only facotrs affecting a seals probability of release. 


## Data
My data comes directly from SR3. It includes the weights of 32 seals (23 of which were released, 9 which died in hospital) from May 2022 - February 2023 for a total of 517 data points. Each data point includes seal ID, date, weight (g), and intake date. 

## Analysis Methods
*Note:* Figure specific analysis as well as thought process is included as markdowns in the .ipynb file. 

I have organized my data into a fashion that will easily be understood by Python. The data has been transferred to a .csv and uploaded to Python. I seperated the deceased (T/F) into linear regression patterns to see if there is a difference in weight gain between seals that were released(F) or deceased(T). I created four plots: cumulative change, cumulative change first 20 days, chagne from last weigh in, and daily change. I detail takeaways from each plot in markdowns for respective plots in the attatched .ipynb. From the *Daily Change* I created a program that takes a users input of *Intake Date*, *Intake Weight*, *Current Date* and *Current Weight** and  will plot where that seal (red dot) lies relative to past seals.

Findings: From this analysis of the data provided, you can not predict if a seal is going to be released or die based on weight and ordinal day alone. The plot is still beneficial in seeing where a seal does lie compared to others but should not be taken as soul source of information for a seals health. 


