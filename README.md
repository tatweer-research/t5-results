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


|                   |                                             t5 | t5-v1.1 |                                       priva_t5 | priva_t5-v1.1 |
|:------------------|-----------------------------------------------:|--------:|-----------------------------------------------:|--------------:|
| policy\_ie\_a     |                                          0.682 |       0 |                                          0.709 |             0 |
| opp\_115          |                                          0.770 |       0 |                                          0.760 |             0 |
| piextract         |                                          0.523 |       0 |                                          0.627 |             0 |
| policy\_detection |                                          0.641 |       0 |                                          0.846 |             0 |
| policy\_ie\_b     |                                          0.444 |       0 |                                          0.468 |             0 |
| policy\_qa        |                                          0.171 |       0 |                                          0.174 |             0 |
| privacy\_qa       |                                          0.532 |       0 |                                          0.474 |             0 |
| title\_generation | rouge1 0.445<br/>rouge2 0.253<br/>rougeL 0.433 |       0 | rouge1 0.462<br/>rouge2 0.262<br/>rougeL 0.450 |             0 |
 

### base


|                   |                                             t5 | t5-v1.1 |                                       priva_t5 | priva_t5-v1.1 |
|:------------------|-----------------------------------------------:|--------:|-----------------------------------------------:|--------------:|
| policy\_ie\_a     |                                          0.736 |       0 |                                          0.777 |             0 |
| opp\_115          |                                          0.791 |       0 |                                          0.716 |             0 |
| piextract         |                                          0.625 |       0 |                                          0.298 |             0 |
| policy\_detection |                                          0.875 |       0 |                                          0.793 |             0 |
| policy\_ie\_b     |                                          0.452 |       0 |                                          0.475 |             0 |
| policy\_qa        |                                          0.182 |       0 |                                          0.186 |             0 |
| privacy\_qa       |                                          0.474 |       0 |                                          0.523 |             0 |
| title\_generation | rouge1 0.539<br/>rouge2 0.350<br/>rougeL 0.526 |       0 | rouge1 0.563<br/>rouge2 0.374<br/>rougeL 0.549 |             0 |


### large


|                   |                                             t5 | t5-v1.1 |                                       priva_t5 | priva_t5-v1.1 |
|:------------------|-----------------------------------------------:|--------:|-----------------------------------------------:|--------------:|
| policy\_ie\_a     |                                          0.761 |       0 |                                          0.791 |             0 |
| opp\_115          |                                          0.816 |       0 |                                          0.810 |             0 |
| piextract         |                                          0.617 |       0 |                                          0.663 |             0 |
| policy\_detection |                                          0.886 |       0 |                                          0.879 |             0 |
| policy\_ie\_b     |                                          0.489 |       0 |                                          0.516 |             0 |
| policy\_qa        |                                          0.194 |       0 |                                              0 |             0 |
| privacy\_qa       |                                              0 |       0 |                                              0 |             0 |
| title\_generation | rouge1 0.557<br/>rouge2 0.362<br/>rougeL 0.544 |       0 | rouge1 0.575<br/>rouge2 0.388<br/>rougeL 0.565 |             0 |


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
 

