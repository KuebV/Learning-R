# Learning-R
Wrapping my head around how R works, but also making it simple to understand while giving examples


```R
# Print a message to the Console
print("Hello World!")
# Hello World!

# Variable Types & Uses

## LOGICAL ----
a <- TRUE
# OUTPUT:
# TRUE

## NUMERIC ----
b <- 12.2
c <- 5
# OUTPUT:
# 12.2
# 5

## Integer ----
d <- 2L
# OUTPUT:
# 2L

## Complex ----
e <- 2+5i
# OUTPUT:
# 2+5i

## Character / String ----

# Character / String
f <- "hello"
# OUTPUT:
# hello


# Methods / Functions

## Vectors ----

# Create a Vector
g <- c("Red", "Orange", "Yellow")
# OUTPUT:
# "Red"    "Orange" "Yellow"

## Lists ----

# Create a list:
# Technical Note: Think of R's lists as the following in C#:
# List<dynamic> RandomStuff = new List<> { new RandomClass, 2, 'A' }
# List's can store different elements inside. Like Vectors
h <- list(12, 3, c(4, 2, 6))
# OUTPUT:
# [[1]]
# [1] 12

# [[2]]
# [1] 3

# [[3]]
# [1] 4 2 6


## Matrice ----

# You don't have to pre-define the Vector, but this is for simplicity sake.

i <- c("c1r1", "c2r1", "c3r1", "c1r2", "c2r2", "c3r2")
j <- matrix(i, nrow=2, ncol=3, byrow = TRUE)

# OUTPUT:
#      [,1]   [,2]   [,3]  
# [1,] "c1r1" "c2r1" "c3r1"
# [2,] "c1r2" "c2r2" "c3r2"


```
