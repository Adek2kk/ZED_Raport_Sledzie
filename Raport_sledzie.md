# Raport śledzi
Adam Chojan  
`r format(Sys.time(), '%d %B, %Y')`  




#Wprowadzenie
Tu będzie krótki opis


#Wykorzystane biblioteki

```r
library(knitr)
```

#Wczytanie danych

```r
url <- "http://www.cs.put.poznan.pl/dbrzezinski/teaching/zed/sledzie.csv"
destfile <- "sledzie.csv"
download.file(url, destfile, mode="wb")
```

```
## Warning in download.file(url, destfile, mode = "wb"): pobrana długość
## 3055616 != zgłoszona długość 6576108
```


```r
mydata = read.csv("sledzie.csv")
```
