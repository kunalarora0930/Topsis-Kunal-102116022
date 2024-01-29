## Topsis-Kunal-102116022

# TOPSIS

Submitted By: **Kunal Arora - 102116022**.

Type: **Package**.

Title: **TOPSIS**.

Version: **1.0.0**.

Date: **28-01-2024**.

Author: **Kunal Arora**.

Maintainer: **Kunal Arora <arorakunal0930@gmail.com>**.

Description: **Evaluation of alternatives based on multiple criteria using TOPSIS method.**.

---

## What is TOPSIS?

**T**echnique for **O**rder **P**reference by **S**imilarity to **I**deal **S**olution
(TOPSIS) originated in the 1980s as a multi-criteria decision making method.
TOPSIS chooses the alternative of shortest Euclidean distance from the ideal solution,
and greatest distance from the negative-ideal solution.

<br>

## Using this package:

```bash
pip install Topsis-Kunal-102116022
```

### In Command Prompt

```bash
topsis data.csv "1,1,1,1" "+,+,-,+" result.csv
```
<br>
The output file contains columns of input file along with two additional columns having **Topsis_score** and **Rank**
