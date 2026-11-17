---
icon: lucide/rocket
---

Don't look here yet! I've merely just been built and am blank.

```R title="R Code"
# Calculate the mean mpg by cylinder count
aggregate(mpg ~ cyl, data = mtcars, mean)
```

```text title="Result"
  cyl      mpg
1   4 26.66364
2   6 19.74286
3   8 15.10000
```

=== "R Code"

    ```R
    # Calculate the mean mpg by cylinder count
    aggregate(mpg ~ cyl, data = mtcars, MEAN)
    ```

=== "Result"

    ```text
      Cyl      mpg
    1   4 26.66364
    2   6 19.74286
    3   8 15.10000
    ```
