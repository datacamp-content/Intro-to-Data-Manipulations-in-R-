---
title: 'Data Manipulations with Dplyr'
description: ""
---

## Insert exercise title here

```yaml
type: VideoExercise 
xp: 50 
key: 3769fa8b9b   
```

`@projector_key`
dd4e6085bd7725c658ebc41bb0ea17f0
---

## Insert exercise title here

```yaml
type: NormalExercise 
xp: 100 
key: 6987bd7422   
```


We can subset only the columns (variable) that matter, by using `select()`.

As an example, take the following call, that selects the variables var1 and var2 from the data frame df.

`select(df, var1, var2)`

You can also select columns based on the index of the column (position of the column). For instance, for selecting columns: one, three and five; you can use:

`select(df, 1,3,5)`

In addition, you can use `:` to select a range of variables and `-` to exclude some variables. For instance:

`select(df, 1:4, -2)`

`select()` does not change the data frame it is called on; you have to explicitly assign the result of `select()` to a variable (or object) to store the result.


`@instructions`


`@hint`


`@pre_exercise_code`

```{r}
cars<-mtcars
```


`@sample_code`

```{r}

```


`@solution`

```{r}

```


`@sct`

```{r}

```

