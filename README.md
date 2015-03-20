# Usage

Currently, only operations on labels and milestones are supported.

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

## Milestones

### List milestones

Example:
```sh
github-multirepos milestones
```

### Create a milestone

Example:
```sh
github-multirepos milestones create 3.5.1 2015-04-14T22:00:00Z 'Release 3.5.1'
github-multirepos milestones create 3.6.0
```

### Rename a milestone

Example:
```sh
github-multirepos milestones mv 3.6.0 v3.6.0
```

### Copy a milestone

Example:
```sh
github-multirepos milestones cp 3.6.*
```

### Remove a milestone

Example:
```sh
github-multirepos milestones rm 3.5.*
```

### Change milestone attributes

Example:
```sh
github-multirepos milestones due 3.5.1 2015-04-14T22:00:00Z
github-multirepos milestones desc 3.5.1 'Release 3.5.1'
```

### Open and close a milestone

Example:
```sh
github-multirepos milestones open 3.5.1
github-multirepos milestones close 3.5.1
```

### Sync milestones

Example:
```sh
github-multirepos milestones sync
```
