

# Class Activity 1

- Try to knit the file at the present stage and see if it compiles.
- You can add `\vspace*{1in}` in the body of this file to produce a vertical space of 1 inches.


## Your Turn 1

---------------------------------------------------

a. Run the following chunk. Comment on the output.


```r
example_data = data.frame(ID = c(1, 2, 3, 4, 5, 6, 7, 8, 9, 10),
                          Greeting = c(rep("Hello", 5), rep("Goodbye",5)),
                          Male = rep(c(TRUE, FALSE), 5),
                          age = runif(n=10, 20,60))

example_data
```

```
   ID Greeting  Male      age
1   1    Hello  TRUE 27.49543
2   2    Hello FALSE 36.77713
3   3    Hello  TRUE 59.80202
4   4    Hello FALSE 47.15347
5   5    Hello  TRUE 59.62777
6   6  Goodbye FALSE 55.09983
7   7  Goodbye  TRUE 56.07272
8   8  Goodbye FALSE 20.76508
9   9  Goodbye  TRUE 29.90842
10 10  Goodbye FALSE 42.04336
```

<details>
<summary><red>Click for answer</red></summary>

*Answer:* 

</details>


\vspace*{1in}

b. What is the dimension of the dataset called 'example_data'?



\vspace*{1in}


---------------------------------------------------

# Your Turn 2


a. Read the dataset `EducationLiteracy` from the [Lock5](https://www.lock5stat.com/datapage2e.html) second edition book.


```r
education_lock5 <- read.csv("https://www.lock5stat.com/datasets2e/EducationLiteracy.csv")
```


b. Print the header (i.e. first 6 elements by default) of the dataset in part a.


```r
head(education_lock5)
```

```
              Country EducationExpenditure Literacy
1         Afghanistan                  3.1     31.7
2             Albania                  3.2     96.8
3             Algeria                  4.3       NA
4             Andorra                  3.2       NA
5              Angola                  3.5     70.6
6 Antigua and Barbuda                  2.6     99.0
```

c. What is the dimension of the dataset in a?


```r
dim(education_lock5)
```

```
[1] 188   3
```
*Answer:*

\vspace*{1in}

d. What type of variables are `Country`, `EducationExpenditure`, and `Literacy`?

*Answer:*


\vspace*{1in}


e. If we would like to use education expenditure to predict the literacy rate of each countries, which variable is the explanatory variable and which one is the response?

*Answer:*



---------------------------------------------------------------------




