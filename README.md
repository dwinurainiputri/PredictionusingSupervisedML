# PredictionusingSupervisedML
This is a repository for my task as an Intern at TSF

#THE SPARK FOUNDTAION:Predict the percentage of an student based on the number of study hours using supervised learning
# TASK-1
#NAME: DWI NUR'AINI PUTRI
#importing libraries
> library(readr)
> library(ggplot2)
Warning message:
package ‘ggplot2’ was built under R version 4.3.3 
> data<-read.csv("http://bit.ly/w-data")
> model<_ Im(Scores~Hours,data)
Error: unexpected symbol in "model<_ Im"
> model<- lm(Scores~Hours,data)
> model

Call:
lm(formula = Scores ~ Hours, data = data)

Coefficients:
(Intercept)        Hours  
      2.484        9.776  

> ggplot(data,aes(x=Hours,y=Scores))+geom_point()
> plot(data)
> abline(model, col="yellow")
> a<-data.frame(Hours=9.25)
> result<-predict(model,a)
> print(result)
       1 
92.90985 
> 
