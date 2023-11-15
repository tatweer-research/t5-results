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


Number of current models including the 8 pretrained on Privaseer: 101

### small


|                   |                                             t5 | t5-v1.1 |                                                 priva_t5 | priva_t5-v1.1 |
|:------------------|-----------------------------------------------:|--------:|---------------------------------------------------------:|--------------:|
| policy\_ie\_a     |                                          0.739 |       0 |                                                    0.714 |             0 |
| opp\_115          |                                          0.753 |       0 |                                                    0.762 |             0 |
| piextract         |                                          0.544 |       0 |                                                    0.602 |             0 |
| policy\_detection |                                          0.796 |       0 |                                                    0.840 |             0 |
| policy\_ie\_b     |                                          0.452 |       0 |                                                    0.413 |             0 |
| policy\_qa        |                                          0.165 |       0 |                                                    0.154 |             0 |
| privacy\_qa       |                                          0.451 |       0 |                                                    0.474 |             0 |
| title\_generation | rouge1 0.330<br/>rouge2 0.190<br/>rougeL 0.318 |       0 | rouge1 __0.349__<br/>rouge2 __0.179__<br/>rougeL __336__ |             0 |


### base


|                   |                                             t5 | t5-v1.1 |                                                   priva_t5 | priva_t5-v1.1 |
|:------------------|-----------------------------------------------:|--------:|-----------------------------------------------------------:|--------------:|
| policy\_ie\_a     |                                           0.76 |       0 |                                                      0.746 |             0 |
| opp\_115          |                                           0.77 |       0 |                                                      0.753 |             0 |
| piextract         |                                          0.548 |       0 |                                                      0.626 |             0 |
| policy\_detection |                                          0.852 |       0 |                                                      0.703 |             0 |
| policy\_ie\_b     |                                          0.459 |       0 |                                                      0.465 |             0 |
| policy\_qa        |                                          0.164 |       0 |                                                      0.126 |             0 |
| privacy\_qa       |                                          0.474 |       0 |                                                      0.490 |             0 |
 | title\_generation | rouge1 0.463<br/>rouge2 0.285<br/>rougeL 0.451 |       0 | rouge1 __0.483__<br/>rouge2 __0.321__<br/>rougeL __0.471__ |             0 |


### large


|                   |                                             t5 | t5-v1.1 |                                                   priva_t5 | priva_t5-v1.1 |
|:------------------|-----------------------------------------------:|--------:|-----------------------------------------------------------:|--------------:|
| policy\_ie\_a     |                                          0.712 |       0 |                                                      0.767 |             0 |
| opp\_115          |                                          0.755 |       0 |                                                      0.788 |             0 |
| piextract         |                                          0.566 |       0 |                                                      0.641 |             0 |
| policy\_detection |                                          0.868 |       0 |                                                      0.874 |             0 |
| policy\_ie\_b     |                                          0.464 |       0 |                                                      0.459 |             0 |
| policy\_qa        |                                          0.157 |       0 |                                                      0.175 |             0 |
| privacy\_qa       |                                          0.490 |       0 |                                                      0.496 |             0 |
 | title\_generation | rouge1 0.473<br/>rouge2 0.278<br/>rougeL 0.461 |       0 | rouge1 __0.504__<br/>rouge2 __0.334__<br/>rougeL __0.492__ |             0 |


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
 

