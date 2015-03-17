# Usage

Currently, only operations on labels are supported.

## Labels

### List labels

Example:
```sh
github-multirepos labels
```

### Create a label

Example:
```sh
github-multirepos labels create bug ffffff
```

### Rename a label

Example:
```sh
github-multirepos labels mv bug feature
```

### Copy a label

Example:
```sh
github-multirepos labels cp effort-*
```

### Remove a label

Example:
```sh
github-multirepos labels rm effort-*
```

### Sync labels

Example:
```sh
github-multirepos labels sync
```
