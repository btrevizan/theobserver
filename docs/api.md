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
`list` **extract**(): extract all the information bellow.
- Number of instances
- Number of features
- Number of targets
- Silhouette (Dunn Index)
- Entropy
