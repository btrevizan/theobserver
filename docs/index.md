# Getting Started
A dataset characteristic extractor for machine learning processing.

## Installation
```bash
$ pip3 install theobserver
```

## Example
```python
from theobserver import Observer

obs = Observer('examples/letter_0.csv', target_i=0)

# Return the number of instances
obs.n_instances()

# Return all characteristics
obs.extract()
```
