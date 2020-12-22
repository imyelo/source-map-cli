# @yelo/source-map-cli

## Install
```bash
$ npm i -g @yelo/source-map-cli
```

## Usage
```bash
$ cat <file> | source-map [line=1] <column>
```

## Example
```bash
$ cat ./index.js.map | source-map 4310
```

```bash
$ cat ./index.js.map | source-map 2 4310
```

## License
Apache-2.0 &copy; [yelo](https://github.com/imyelo), 2020 - present
