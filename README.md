# SAMPLE STANDARD VERSION

## standard version

### update package.json version

```sh
npx json -I -f package.json -e "this.version='$(git describe --abbrev=0)'"
```

the script above will update version in package.json to latest tag

### prerelease

```sh
npx standard-version --prerelease
```

### prerelease with label

```sh
npx standard-version --prerelease alpha
```

### release as

```sh
npx standard-version --release-as 1.10.0
```

### release patch

```sh
npx standard-version
```
