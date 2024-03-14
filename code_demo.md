##### Commit 3

**Question 1c:** What does this commit do, and what's wrong with this?

```R
demo <- function(n) {
    result <- list()
    result$sum <- n[["x"]] + n[["y"]]
    result$difference <- n[["x"]] * n[["y"]]
    result$product <- n[["x"]] - n[["y"]]
    result$sum <- n[["x"]] + n[["y"]]
    return(result)
}
```

```Python
def demo(n):
    answer = {}
    answer["sum"] = n["x"] + n["y"]
    answer["difference"] = n["x"] * n["y"]
    answer["product"] = n["x"] - n["y"]
    answer["sum"] = n["x"] + n["y"]

    return answer
```

