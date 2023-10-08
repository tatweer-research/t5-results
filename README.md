## PrivacyGLUE

The finetuning is based on the [PrivacyGLUE](https://github.com/infsys-lab/privacy-glue) dataset proposed by [Shankar et al.](https://www.mdpi.com/2076-3417/13/6/3701).


## Tasks

- OPP-115
- PI-Extract
- Policy-Detection
- PolicyIE-A
- PolicyIE-B
- PolicyQA
- PrivacyQA

## Available Models([here](https://huggingface.co/alzoubi36))


Number of current models including the 8 pretrained on Privaseer: 92

### small


|                   |                                             t5 | t5-v1.1 |                                                   priva_t5 | priva_t5-v1.1 |
|:------------------|-----------------------------------------------:|--------:|-----------------------------------------------------------:|--------------:|
| policy\_ie\_a     |                                          0.682 |       0 |                                                  __0.709__ |             0 |
| opp\_115          |                                      __0.770__ |       0 |                                                      0.760 |             0 |
| piextract         |                                          0.523 |       0 |                                                  __0.627__ |             0 |
| policy\_detection |                                          0.641 |       0 |                                                  __0.846__ |             0 |
| policy\_ie\_b     |                                          0.444 |       0 |                                                  __0.468__ |             0 |
| policy\_qa        |                                          0.171 |       0 |                                                  __0.174__ |             0 |
| privacy\_qa       |                                      __0.532__ |       0 |                                                      0.474 |             0 |
| title\_generation | rouge1 0.445<br/>rouge2 0.253<br/>rougeL 0.433 |       0 | rouge1 __0.462__<br/>rouge2 __0.262__<br/>rougeL __0.450__ |             0 |
 

### base


|                   |                                             t5 | t5-v1.1 |                                                   priva_t5 | priva_t5-v1.1 |
|:------------------|-----------------------------------------------:|--------:|-----------------------------------------------------------:|--------------:|
| policy\_ie\_a     |                                          0.736 |       0 |                                                  __0.777__ |             0 |
| opp\_115          |                                      __0.791__ |       0 |                                                      0.716 |             0 |
| piextract         |                                      __0.625__ |       0 |                                                      0.298 |             0 |
| policy\_detection |                                      __0.875__ |       0 |                                                      0.793 |             0 |
| policy\_ie\_b     |                                          0.452 |       0 |                                                  __0.475__ |             0 |
| policy\_qa        |                                          0.182 |       0 |                                                  __0.186__ |             0 |
| privacy\_qa       |                                          0.474 |       0 |                                                  __0.523__ |             0 |
| title\_generation | rouge1 0.539<br/>rouge2 0.350<br/>rougeL 0.526 |       0 | rouge1 __0.563__<br/>rouge2 __0.374__<br/>rougeL __0.549__ |             0 |


### large


|                   |                                             t5 | t5-v1.1 |                                                   priva_t5 | priva_t5-v1.1 |
|:------------------|-----------------------------------------------:|--------:|-----------------------------------------------------------:|--------------:|
| policy\_ie\_a     |                                          0.761 |       0 |                                                  __0.791__ |             0 |
| opp\_115          |                                      __0.816__ |       0 |                                                      0.810 |             0 |
| piextract         |                                          0.617 |       0 |                                                  __0.663__ |             0 |
| policy\_detection |                                      __0.886__ |       0 |                                                      0.879 |             0 |
| policy\_ie\_b     |                                          0.489 |       0 |                                                  __0.516__ |             0 |
| policy\_qa        |                                          0.194 |       0 |                                                  __0.207__ |             0 |
| privacy\_qa       |                                          0.540 |       0 |                                                  __0.644__ |             0 |
| title\_generation | rouge1 0.557<br/>rouge2 0.362<br/>rougeL 0.544 |       0 | rouge1 __0.575__<br/>rouge2 __0.388__<br/>rougeL __0.565__ |             0 |


### 3b


|                   |   t5 |   t5-v1.1 |   priva_t5 |   priva_t5-v1.1 |
|:------------------|-----:|----------:|-----------:|----------------:|
| policy\_ie\_a     |    0 |         0 |          0 |               0 |
| opp\_115          |    0 |         0 |          0 |               0 |
| piextract         |    0 |         0 |          0 |               0 |
| policy\_detection |    0 |         0 |          0 |               0 |
| policy\_ie\_b     |    0 |         0 |          0 |               0 |
| policy\_qa        |    0 |         0 |          0 |               0 |
| privacy\_qa       |    0 |         0 |          0 |               0 |
 

