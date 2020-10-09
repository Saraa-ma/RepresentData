# RepresentData
How to Convert Horizontal to Vertical Data Format with Pandas
## Input Data Format (Horizontal)

| Transaction | Item01 | Item02 | Item03 |
| ----------- | ------ | ------ | :----- |
| T1          | A      | B      |        |
| T2          | B      | C      | D      |
| T3          | C      | B      |        |
| T4          | A      | C      |        |


## Output Data Format (Vertical)

| Transaction | T01  | T02  | T03  | T04  |
| ----------- | ---- | ---- | :--- | ---- |
| A           | 1    | 0    | 0    | 1    |
| B           | 1    | 1    | 1    | 0    |
| C           | 0    | 1    | 1    | 1    |
| D           | 0    | 1    | 0    | 0    |
