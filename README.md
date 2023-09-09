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


|                   |       t5 |   t5-v1.1 |   priva_t5 |   priva_t5-v1.1 |
|:------------------|---------:|----------:|-----------:|----------------:|
| policy\_ie\_a     | 0        |  0        |   0        |        0        |
| opp\_115          | 0.801986 |  0        |   0.586887 |        0        |
| piextract         | 0.445171 |  0        |   0.44924  |        0        |
| policy\_detection | 0.841432 |  0.877238 |   0.905371 |        0.163683 |
| policy\_ie\_b     | 0.395435 |  0        |   0.332594 |        0        |
| policy\_qa        | 0.979769 |  0.970617 |   0.936416 |        0.978805 |
| privacy\_qa       | 0.895768 |  0.900016 |   0.900161 |        0        |
 

### base


|                   |       t5 |   t5-v1.1 |   priva_t5 |   priva_t5-v1.1 |
|:------------------|---------:|----------:|-----------:|----------------:|
| policy\_ie\_a     | 0        |  0        |  0         |        0        |
| opp\_115          | 0.833844 |  0        |  0         |        0.817839 |
| piextract         | 0.617185 |  0        |  0         |        0.456643 |
| policy\_detection | 0.887468 |  0.861893 |  0.808184  |        0.838875 |
| policy\_ie\_b     | 0.442244 |  0.219717 |  0.0484218 |        0        |
| policy\_qa        | 0.986513 |  0.957852 |  0.953757  |        0.975915 |
| privacy\_qa       | 0.900016 |  0.900016 |  0         |        0        |
 

### large


|                   |       t5 |   t5-v1.1 |   priva_t5 |   priva_t5-v1.1 |
|:------------------|---------:|----------:|-----------:|----------------:|
| policy\_ie\_a     | 0        |         0 |   0        |               0 |
| opp\_115          | 0        |         0 |   0        |               0 |
| piextract         | 0.630362 |         0 |   0.504791 |               0 |
| policy\_detection | 0.933504 |         0 |   0.161125 |               0 |
| policy\_ie\_b     | 0.448525 |         0 |   0        |               0 |
| policy\_qa        | 0        |         0 |   0.926301 |               0 |
| privacy\_qa       | 0        |         0 |   0        |               0 |
 

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
 

