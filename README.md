# Mice Down Syndrome through Protein Expressions

## Description of the Data Set 

The data set consists of the expression levels of 77 proteins that produced detectable signals in the nuclear fraction of the cortex. There are 38 Control mice and 34 Trisomic mice (Down syndrome), for a total of 72 mice. In the experiments, 15 measurements were registered of each protein per mouse. 
Therefore, for Control mice, there are $38*15 = 570$ measurements, and for Trisomic mice, there are $34*15 = 510$ measurements. The dataset contains a total of 1080 measurements per protein. Each measurement can be considered as an independent mouse.  
Some mice have been stimulated to learn (context-shock) and others have not (shock-context) and in order to assess the effect of the drug memantine in recovering the ability to learn in trisomic mice, some mice have been injected with the drug and others have not.

The data set includes the following features:

[1] Mouse ID

[2:78] Values of expression levels of 77 proteins; the names of proteins are followed by N indicating that they were measured in the nuclear fraction. 

[79] Genotype: control (c) or trisomy (t)

[80] Treatment type: memantine (m) or saline (s)

[81] Behavior: context-shock (CS) or shock-context (SC)

[82] Class:
*  c-CS-s: control mice, stimulated to learn, injected with saline (9 mice)
*  c-CS-m: control mice, stimulated to learn, injected with memantine (10 mice)
*  c-SC-s: control mice, not stimulated to learn, injected with saline (9 mice)
*  c-SC-m: control mice, not stimulated to learn, injected with memantine (10 mice)
*  t-CS-s: trisomy mice, stimulated to learn, injected with saline (7 mice)
*  t-CS-m: trisomy mice, stimulated to learn, injected with memantine (9 mice)
*  t-SC-s: trisomy mice, not stimulated to learn, injected with saline (9 mice)
*  t-SC-m: trisomy mice, not stimulated to learn, injected with memantine (9 mice)

## Aim
The aim of this project is to identify a subset of proteins that is discriminant between the classes.
## Objective
Perform featrure selection process and develop a classification model. 
## Methods
Decision Tree and Random Forest, Linear and quadratic Discriminant Analysis
## Inference
Explore how the final predictor's (discriminant proteins) influence the $class$ of mice.