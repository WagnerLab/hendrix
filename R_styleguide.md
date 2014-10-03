Title
=======================
 
Section A
--------------
Text about the section. There will be a chunk of code about naming variables.
 
```{r naming_vars}
df_name <- read.csv('http://stanford.edu/class/psych252/data/caffeine.csv')
numConstant <- 200
```
 
Naming Functions
------------------
```{r naming_functions}
CalculateSum <- function(a, b){
  # Calculates the sum of two numbers
  # Args:
  #   a: one number to be added
  #   b: another number to be added
  #
  # Returns: 
  #   The sum of a and b.
  
  c <- a + b
  return c
}
```
 
If/Else Statements
---------------------
```{r if_else}
if (condition) {
  one or more lines
} else {
  one or more lines
}
```