### Look up! GSS.csv is just above the README.md file!

### Use the following R codes to load the file in your R studio. 
library(RCurl)
x <- getURL("https://raw.githubusercontent.com/DASI2015/Project-Dataset/master/GSS.csv")
GSS <- read.csv(text = x)

