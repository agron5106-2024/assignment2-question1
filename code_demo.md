##### Commit 5

**Question 1e:** What are the differences between this and the previous commit? Does it matter? Why or Why not?

```R
demo <- function(n) {
    result <- list()
    result$sum <- n[["y"]] + n[["x"]]
    result$ratio <- n[["x"]] + n[["y"]]
    result$difference <- n[["x"]] - n[["y"]]
    result$product <- n[["x"]] * n[["y"]]
    return(result)
}
```

```Python
def demo(n):
    answer = {}
    answer["sum"] = n["x"] + n["y"]
    answer["ratio"] = n["x"] + n["y"]
    answer["difference"] = n["x"] - n["y"]
    answer["product"] = n["x"] * n["y"]
    return answer
```

