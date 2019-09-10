# manypkg

`manypkg` is a CLI to make working in multi-package repos easier based on some of my experiences working in multi-package repos, conversations with other people and lots of learnings from `bolt` and `bolt-check`.

## Install

```
yarn add @manypkg/cli
```

## Usage

### Checker

```
yarn manypkg check
```

```
yarn manypkg fix
```

### Script Runner

> Note: The following is not implemented currently

### In the root of a multi-package repo

```
yarn m <pkgName> add <depDescriptor>
```

```
yarn m <pkgName> <scriptName>
```

```
yarn m <binaryFromNodeModulesName>
```

### In a package

```
yarn m add <depDescriptor>
```

```
yarn m <scriptName>
```

```
yarn m <binaryFromNodeModulesName>
```
