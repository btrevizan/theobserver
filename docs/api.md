# theobserver's API

`class` theobserver.**Observer**(*filepath, target_i*): return a Observer object.

- `string` **filepath**: relative/absolute path to a CSV file.
- `{0, -1}` **target_i**: the target's column index. The default is -1.

### Methods
`int` **n_instances**(): get the number of instances.

---
`int` **n_features**(): get the number of instances.

---
`int` **n_targets**(): get the number of targets.

---
`float` **silhouette**(): get the mean silhouette coefficient for all samples.

---
`float` **entropy**(): get the samples' entropy.

---
`float` **unbalanced**(): entropy / log N, where, N is the number of classes.

---
`float` **n_binary_features**(): get the number of binary features, i.e., features with only 2 labels.

---
`float` **majority_class_size**(): get the number of instances labeled with the most frequent class.

---
`float` **minority_class_size**(): get the number of instances labeled with the least frequent class.

---
`float` **features_with_na**(*na_values=[]*): get the number of features with missing values.

**Arguments**
- na_values: *list (default [])*\
A list of strings or ints to interpret as NaN values.

---
`float` **missing_values**(*na_values=[]*): get the number of missing values.

**Arguments**
- na_values: *list (default [])*\
A list of strings or ints to interpret as NaN values.

---
`list` **extract**(): extract all the information bellow.
- Number of instances
- Number of features
- Number of targets
- Silhouette (Dunn Index)
- Entropy
- Unbalanced
- Number of binary features
- Majority class size
- Minority class size
- Number of features with missing values
- Number of missing values

