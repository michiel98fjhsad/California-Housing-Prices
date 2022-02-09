
data <- read.csv("C:/Users/michi/OneDrive/Master/04. Big Data Econometrics/Exercises/housing.csv")
data <- na.omit(dat)
summary(data)
hist(data$median_house_value)
dim(data)
data <- data[data$median_house_value < 500000, ] #deletes 985 houses
