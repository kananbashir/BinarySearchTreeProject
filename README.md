# BinarySearchTreeProject

## 1. Steps [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

Root is 7

If picked number higher that root it will go down to left otherwise it'll go down right


**1 >> 5 is smaller than 7 so it's going down to rightside:**
 ```
                 7
                /
               5
```
               
**2 >> 1 is smaller than 7 and 5 so it's going down to rightside:**
```
                  7
                /
               5
              /
             1
```
             
**3 >> 8 is higher than 7 and so it's going down to leftside:**
```
                  7
                /   \
               5     8
              /
             1
```
             
**4 >> 8 is higher than 7 and so it's going down to leftside:**
```
                  7
                /   \
               5     8
              /
             1
```

**5 >> 3 is smaller than 7 and 5 but bigger than 1 so it's going down to leftside seven and rightside of one:**
```
                  7
                /   \
               5     8
              / 
             1
              \
                3
```

**6 >> 6 is smaller than 7 but bigger than 5 so it's going down to leftside of seven and rightside of five:**
```
                  7
                /   \
               5     8
              / \
             1   6
              \
                3
```

**7 >> 0 is smaller than 7 so it's going down to leftside:**
```
                  7
                /   \
               5     8
              / \
             1   6
            / \
           0   3
```

**8 >> 9 is higher than 7 so it's going down to rightside:**
```
                  7
                /   \
               5     8
              / \     \
             1   6      9
            / \
           0   3
```

**9 >> 4 is smaller than 7 and 5 but it's higher than 3 so it's going down to rightside of three:**
```
                  7
                /   \
               5     8
              / \     \
             1   6      9
            / \
           0   3
                \
                 4
```

**10 >> 2 is smaller than 7 and 3 so it's going down to leftside of three:**
```
                  7
                /   \
               5     8
              / \     \
             1   6      9
            / \
           0   3
             /  \
            2    4
```
