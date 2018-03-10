# Getting Started
A dataset characteristic extractor for machine learning processing.

## Installation
```bash
$ pip3 install theobserver
```

## Dependencies
```bash
$ pip3 install pandas==0.20.3 scikit-learn==0.19.0
```

## Example
```python
from theobserver import Observer

obs = Observer('examples/letter_0.csv', target_i=0)

# Return the number of instances
obs.n_instances()

# Return all characteristics
# [n_instances, n_features, n_targets, silhouette, entropy]
obs.extract()
```
