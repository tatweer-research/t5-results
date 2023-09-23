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


|                   |    t5 | t5-v1.1 |  priva_t5 | priva_t5-v1.1 |
|:------------------|------:|--------:|----------:|--------------:|
| policy\_ie\_a     | 0.831 |   0.804 |     0.799 |     __0.835__ |
| opp\_115          | 0.825 |   0.325 | __0.832__ |         0.801 |
| piextract         | 0.552 |   0.437 | __0.627__ |         0.505 |
| policy\_detection | 0.907 |   0.875 | __0.928__ |         0.882 |
| policy\_ie\_b     | 0.417 |   0.164 | __0.431__ |         0.413 |
| policy\_qa        | 0.172 |   0.114 | __0.174__ |         0.144 |
| privacy\_qa       | 0.900 |   0.900 | __0.900__ |         0.900 |
 

### base


|                   |        t5 |   t5-v1.1 |  priva_t5 | priva_t5-v1.1 |
|:------------------|----------:|----------:|----------:|--------------:|
| policy\_ie\_a     |     0.858 |     0.866 | __0.874__ |         0.836 |
| opp\_115          |     0.845 |     0.325 |     0.814 |     __0.860__ |
| piextract         | __0.625__ |     0.192 |     0.300 |         0.610 |
| policy\_detection |     0.934 | __0.939__ |     0.905 |         0.931 |
| policy\_ie\_b     |     0.437 |     0.425 |     0.454 |     __0.463__ |
| policy\_qa        |     0.182 |     0.159 | __0.186__ |         0.144 |
| privacy\_qa       |     0.900 |     0.900 | __0.902__ |         0.900 |
 

### large


|                   | t5 | t5-v1.1 | priva_t5 | priva_t5-v1.1 |
|:------------------|---:|--------:|---------:|--------------:|
| policy\_ie\_a     |  0 |       0 |        0 |             0 |
| opp\_115          |  0 |       0 |        0 |             0 |
| piextract         |  0 |       0 |        0 |             0 |
| policy\_detection |  0 |       0 |        0 |             0 |
| policy\_ie\_b     |  0 |       0 |        0 |             0 |
| policy\_qa        |  0 |       0 |        0 |             0 |
| privacy\_qa       |  0 |       0 |        0 |             0 |
 

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
 

