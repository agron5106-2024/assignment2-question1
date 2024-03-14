##### Commit 4

**Question 1d:** Used `git diff` to help you identify the changes between this and the previous commits (commit 3).

```R
demo <- function(n) {
    result <- list()
    result$sum <- n[["x"]] + n[["y"]]
    result$product <- n[["x"]] * n[["y"]]
    result$difference <- n[["x"]] - n[["y"]]
    result$ratio <- n[["x"]] + n[["y"]]
    return(result)
}
```

```Python
def demo(n):
    answer = {}
    answer["sum"] = n["x"] + n["y"]
    answer["product"] = n["x"] * n["y"]
    answer["difference"] = n["x"] - n["y"]
    answer["ratio"] = n["x"] + n["y"]
    return answer
```

