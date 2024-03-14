##### Commit Final

**Final output:** Use this as a starting point for Question 2.

This function takes one argument with two non-zero numeric numbers ("x" and "y").

```R
demo <- function(n) {
    result <- list()
    result$sum <- n[["x"]] + n[["y"]]
    result$difference <- n[["x"]] - n[["y"]]
    result$product <- n[["x"]] * n[["y"]]
    result$ratio <- n[["x"]] / n[["y"]]
    return(result)
}
```

```Python
def demo(n):
    answer = {}
    answer["sum"] = n["x"] + n["y"]
    answer["difference"] = n["x"] - n["y"]
    answer["product"] = n["x"] * n["y"]
    answer["ratio"] = n["x"] / n["y"]
    return answer
```
