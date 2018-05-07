Tool for extracting URLs from Firefox session files.

FYI: browser is a bad place to store your URLs.

### Usage

```
wims [--show-titles] [path]
```

### Example

```
wims recovery.jsonlz4
```

Or simply (Windows):

```
wims
```

### Dependencies

```
pip3 install lz4
```

### See also

- https://github.com/andikleen/lz4json
- https://gist.github.com/Tblue/62ff47bef7f894e92ed5
- https://github.com/lilydjwg/mozlz4-tool
